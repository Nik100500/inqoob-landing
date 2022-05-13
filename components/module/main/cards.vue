<template>
  <div class="text-white container mx-auto flex flex-col space-y-6 w-full">
    <div class="flex flex-col lg:flex-row items-end lg:space-x-6">
      <div class=" flex flex-col w-full lg:w-1/3 relative basic-card order-2 lg:order-1 mb-6 lg:mb-0">
        <div class="cards-background absolute left-0 top-0 w-full h-full z-0"></div>  
        <div class="w-full h-full px-6 pb-6 pt-2 z-10">
          <div class="text-120px opacity-20 font-bold mb-8">2</div>
          <div class="text-30px sm:text-36px font-bold mb-2">$700</div>
          <div class="mb-6">to the card and $100 to the account</div>
          <div class="opacity-60 flex flex-row mb-3">
            <div>
              <IconPlus class="w-6" />
            </div>
            PRO function for 2 months
          </div>
          <div class="opacity-60 flex flex-row">
            <div>
              <IconPlus class="w-6" />
            </div>
            5% increased percentage from the affiliate program and lifetime discount of 5%
          </div>
        </div>
      </div>
      <div class=" flex flex-col w-full lg:w-1/3 relative long-card order-1 lg:order-2 mb-6 lg:mb-0">
        <div class="ellipse-yellow"></div>
        <div class="cards-background absolute left-0 top-0 w-full h-full z-0"></div>  
        <div class="w-full h-full px-6 pb-6 pt-2 z-10">
          <div class="text-120px opacity-20 font-bold mb-8">1</div>
          <div class="text-30px sm:text-36px font-bold mb-2">$1000</div>
          <div class="mb-6">to the card and $100 to the account</div>
          <div class="opacity-60 flex flex-row mb-3">
            <div>
              <IconPlus class="w-6" />
            </div>
            PRO function for 3 months
          </div>
          <div class="opacity-60 flex flex-row">
            <div>
              <IconPlus class="w-6" />
            </div>
            10% increased percentage from the affiliate program and lifetime discount of 10%
          </div>
        </div>
      </div>
      <div class=" flex flex-col w-full lg:w-1/3 relative basic-card order-3">
        <div class="cards-background absolute left-0 top-0 w-full h-full z-0"></div>  
        <div class="w-full h-full px-6 pb-6 pt-2 z-10">
          <div class="text-120px opacity-20 font-bold mb-8">3</div>
          <div class="text-30px sm:text-36px font-bold mb-2">$500</div>
          <div class="mb-6">to the card and $100 to the account</div>
          <div class="opacity-60 flex flex-row mb-3">
            <div>
              <IconPlus class="w-6" />
            </div>
            PRO function for 1 month
          </div>
          <div class="opacity-60 flex flex-row">
            <div>
              <IconPlus class="w-6" />
            </div>
            5% increased percentage from the affiliate program and lifetime discount of 5%
          </div>
        </div>
      </div>
    </div>
    <!-- flex flex-col space-y-6 lg:flex-row lg:space-y-0 items-end lg:space-x-6 -->
    <div class="flex flex-col space-y-6 lg:flex-row lg:space-y-0 items-end lg:space-x-6">
      <div class="flex w-full lg:w-1/2 relative">
        <div class="cards-background absolute left-0 top-0 w-full h-full z-0"></div> 
        <div class=" flex flex-row w-full items-start h-full p-6 z-10"> 
          <div class="text-40px opacity-20 font-bold mr-10">4-5</div> 
          <div class="flex flex-col">

            <div class="text-30px sm:text-36px font-bold mb-2">$150</div>
              <div class="">to the card and $50 to the account</div>
          </div>
          
        </div>
      </div>
      <div class="flex w-full lg:w-1/2 relative">
        <div class="cards-background absolute left-0 top-0 w-full h-full z-0"></div> 
        <div class=" flex flex-row w-full items-start h-full p-6 z-10"> 
          <div class="text-40px opacity-20 font-bold mr-10">6-10</div>
          <div class="flex flex-col">

            <div class="text-30px sm:text-36px font-bold mb-2">$100</div>
              <div class="">to the card and $50 to the account</div>
          </div>
          
        </div>
      </div>
    </div>
  </div>
    
</template>


<style lang="scss" scoped>
.cards-background {
  background: linear-gradient(112.2deg, #1B2024 15.47%, #252B30 111.05%);
  box-shadow: 0px 2px 12px 1px rgba(0, 0, 0, 0.08);
  backdrop-filter: blur(16px);
  border-radius: 16px;
  opacity: .3;
}
.basic-card {
  @media screen and (min-width: 1024px) {
  
  height: 414px;
    
  }
}
.long-card {
  @media screen and (min-width: 1024px) {
  height: 480px;
    
  }
}
.ellipse-yellow {
  position: absolute;
  width: 316.29px;
  height: 178.8px;
  top: 20px;
  background: #F9ED37;
  filter: blur(136px);
  transform: rotate(35.02deg); 
  @media screen and (min-width:640px) {
    top: -50px;
    filter: blur(136px);
    transform: rotate(35.02deg); 
    width: 516.29px;
    height: 278.8px;

  }
}
</style>