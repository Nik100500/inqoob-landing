<template>
  <header class="header container mx-auto px-0">
    <nav class="select-none flex justify-between items-center text-normal font-semibold pt-12 pb-24 sm:py-8 absolute container z-20">
      <div class="header-navbar flex justify-center items-center w-full">
        
        <div class="w-56 sm:w-40 relative">
          <div class="block sm:hidden ellipse-white"></div>
          <NuxtLink to="/">
            <LogoInqoob />
            
            <!-- <LogoFeedbackBlackText v-else/> -->
          </NuxtLink>
        </div>
      </div>
    </nav>
  </header>
</template>

<style lang="scss">

  .ellipse-white {
    position: absolute;
    width: 315px;
    height: 106px;
    left: -70px;
    top: -111px;

    background: rgba(255, 255, 255, 0.8);
    filter: blur(73px);
  }
</style>
