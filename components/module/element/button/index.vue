<template>
  <div>
    <a target="_blank" href="https://t.me/sfgsrg_bot" class="
      px-8 md:px-12 py-3 text-normal leading-normal font-semibold rounded-2xl text-white border border-blue-inqoob
      transition duration-150 ease-in-out bg-blue-inqoob
      hover:bg-blue-inqoob-hover hover:border-feedback-active
      active:bg-blue-inqoob-active active:border-blue-inqoob-active"
      >
      {{text}}
      </a>
  </div>
</template>
<script>
export default {
  props: {
    text: {
      type: String,
      default: "start chalange"
    }
  }
}
</script>