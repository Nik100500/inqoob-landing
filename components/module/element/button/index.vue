<template>
  <div class="relative">
    <a target="_blank" href="https://forms.gle/siNZiQEWg7myg1Uj7" class="button-challenge uppercase sm:capitalize
      px-8 md:px-12 py-3 text-normal leading-normal font-semibold rounded-2xl text-white border border-blue-inqoob
      transition duration-150 ease-in-out bg-blue-inqoob
      hover:bg-blue-inqoob-hover hover:border-blue-inqoob-hover
      active:bg-blue-inqoob-active active:border-blue-inqoob-active flex flex-row whitespace-nowrap"
      >
    <div class="ellipse-blue w-full h-full">
    </div>
      <IconMediaTelegramButton class="mr-2.5 mt-1" />
      {{text}}
      </a>
  </div>
</template>
<script>
export default {
  props: {
    text: {
      type: String,
      default: "start challenge"
    }
  }
}
</script>

<style lang="scss" scoped>
.button-challenge {
  z-index: 10;
}
  .ellipse-blue {
    position: absolute;
    width: 315px;
    height: 86px;
    left: -25px;
    top: -17px;

    background: #1583FE;
    opacity: 1;
    filter: blur(113px);
    z-index: 0;
  }
</style>