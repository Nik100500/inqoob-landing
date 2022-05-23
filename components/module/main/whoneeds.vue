<template>
<div>
  <div class="ellipse-blue"></div>
  <div class="flex flex-row justify-between container mx-auto w-full"> 
    <div class="flex flex-col w-full sm:w-5/12 space-y-8 sm:space-y-10">
      <div class="text-white uppercase mb-2 sm:mb-6 text-center sm:text-left text-25px sm:text-36px font-bold">
        who needs it?
      </div>
      <div class="flex flex-col text-center sm:text-left">
        <div class="mb-2 sm:mb-4 text-22px sm:text-24px font-bold text-green-inqoob uppercase">
          technical specialists
        </div>
        <div class="text-gray-inqoob">
          Offline mode and collaboration mode are both available.
        </div>
      </div>
      <div class="flex flex-col text-center sm:text-left">
        <div class="mb-2 sm:mb-4 text-22px sm:text-24px font-bold text-green-inqoob uppercase">
          marketers
        </div>
        <div class="text-gray-inqoob">
          Test your ideas for free and keep track of them using the constructor's extensive analytics.
        </div>
      </div>
      <div class="flex flex-col text-center sm:text-left">
        <div class="mb-2 sm:mb-4 text-22px sm:text-24px font-bold text-green-inqoob uppercase">
          Entrepreneurs
        </div>
        <div class="text-gray-inqoob">
          Use the Inqoob Store to automate your company and discover ready-made answers.
        </div>
      </div>
      <div class="flex flex-col text-center sm:text-left">
        <div class="mb-2 sm:mb-4 text-22px sm:text-24px font-bold text-green-inqoob uppercase">
          Freelancers
        </div>
        <div class="text-gray-inqoob">
          Convenient and quick working process from any device and the implementation of chatbots in your projects.
        </div>
      </div>
      <div class="flex flex-col text-center sm:text-left">
        <div class="mb-4 text-22px sm:text-24px font-bold text-green-inqoob uppercase">
          Beginners
        </div>
        <div class="text-gray-inqoob">
          The opportunity to learn and create chatbots for free in a new generation platform.
        </div>
      </div>
    </div>
    <div class="hidden sm:flex sm:flex-col sm:w-1/2 overflow-hidden justify-center items-center">
      <div class="image flex justify-center items-center">
        <img class="h-full min-w-content" :src="require('../../../assets/img/company.jpg')" alt="">
      </div>
    </div>
  </div>
</div>

</template>

<style lang="scss" scoped>
 .image {
   width: 1000px;
 }
</style>
