<template>
  <div class="bg-black-inqoob">
    <div class="min-h-screen bg-black-inqoob overflow-x-hidden">
      <ModuleMain class="mb-40"/>
      <ModuleMainCards class="mb-24"/>
      <ModuleMainBenefits class="mb-32 sm:mb-40"/>
      <ModuleMainInqoob class="mb-32 sm:mb-40"/>
      <ModuleMainWhoneeds class="pb-28 sm:pb-52"/>
    </div>
    <div class="min-h-screen bg-blue-inqoob-bg overflow-x-hidden">
      <ModuleMainTasks class="pb-24"/>
    </div>
    <div class="bg-black-inqoob overflow-x-hidden">
      <ModuleMainTimer class="pb-44"/>
    </div>
    <div class="bg-white bg-opacity-10 overflow-x-hidden">
      <ModuleMainFeatures class="pb-32"/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;600;700&display=swap');
html {
  font-family: 'Montserrat', sans-serif;
}
</style>

