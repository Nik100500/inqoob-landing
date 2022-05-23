<template>
  <div class="relative">
    <div class="ellipse-green hidden sm:block"></div>
    <div class="ellipse-blue hidden sm:block"></div>
    <div class="container mx-auto text-white">
      <div class="uppercase text-center font-bold text-25px sm:text-36px mb-10 sm:mb-16">
        and more benefits
      </div>
      <div class="w-full flex flex-col space-y-6">
        <div class="flex flex-col space-y-6 lg:flex-row lg:space-y-0 items-end lg:space-x-6 ">
          <div class="w-full lg:w-2/3 card">
            <div class=" flex flex-col w-full items-start h-full p-6 z-10"> 
              <div class="text-48px sm:text-56px font-bold mb-4">$50</div> 
              <div class="">Starting fund of in your account</div>
            </div>
          </div>
          <div class="w-full lg:w-1/3 card">
            <div class=" flex flex-col w-full items-start h-full p-6 z-10"> 
              <div class="text-48px sm:text-56px font-bold mb-4">x2</div> 
              <div class="">Double everything X2 - A special bonus that will be valid for 48 hours</div>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-6 lg:flex-row lg:space-y-0 items-end lg:space-x-6 z-10">
          <div class="w-full lg:w-1/3 card">
            <div class=" flex flex-col w-full items-start h-full p-6 z-10"> 
              <div class="text-48px sm:text-56px font-bold mb-4">24/7</div> 
              <div class="">Prioritized support</div>
            </div>
          </div>
          <div class="w-full lg:w-1/3 card">
            <div class=" flex flex-col w-full items-start h-full p-6 z-10"> 
              <div class="text-48px sm:text-56px font-bold mb-4 uppercase">Level +</div> 
              <div class="">Assignment of a special rank</div>
            </div>
          </div>
          <div class="w-full lg:w-1/3 card">
            <div class=" flex flex-col w-full items-start h-full p-6 z-10"> 
              <div class="text-48px sm:text-56px font-bold mb-4">1K</div> 
              <div class="">Adding to the private developers' chat</div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex justify-center w-full mt-12">
        <ModuleElementButton text="start challenge" />
      </div>
    </div>
  </div>
  
</template>

<style lang="scss" scoped>
  .card {
    background: linear-gradient(112.2deg, #1B2024 15.47%, #252B30 111.05%);
    box-shadow: 0px 2px 12px 1px rgba(0, 0, 0, 0.08);
    border-radius: 16px;
    @media screen and (min-width: 640px) {
      height: 218px;
    }
  }
  .ellipse-green {
    position: absolute;
    width: 192.33px;
    height: 295.67px;
    left: -135.92px;

    background: #20FF80;
    opacity: 0.57;
    filter: blur(115px);
    transform: rotate(38.96deg);
  }
  .ellipse-blue {
    position: absolute;
    width: 192.33px;
    height: 295.67px;
    right: -135.92px;
    top: 335.92px;

    background: #18A0FB;
    opacity: 0.57;
    filter: blur(115px);
    transform: rotate(38.96deg);
  }
</style>