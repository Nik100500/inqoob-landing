<template>
  <div class="container mx-auto text-white text-18px sm:text-24px">
    <div class="text-25px sm:text-36px font-bold flex w-full justify-center uppercase mt-28">
      complete 5 easy tasks
    </div>
    <div class="flex flex-col items-center sm:items-start text-center sm:text-left space-y-8 sm:space-y-0 sm:flex-row justify-center py-8 sm:py-16 w-full border-opacity-10 border-b border-white">
      <div class="text-120px opacity-20 w-2/12 font-bold">
        1
      </div>
      <div class="flex flex-col w-full sm:w-8/12 justify-center">
        <div>Subscribe to our social networks</div>
        <div class="flex flex-row space-x-4 justify-center sm:justify-start mt-4 sm:mt-0">
          
          <a target="_blank" href="https://instagram.com/eng_inqoob?utm_medium=copy_link"><IconTasksInstagram  class="w-24 sm:w-12"/></a>
          <a target="_blank" href="https://www.facebook.com/groups/686605689152886/"><IconTasksFacebook  class="w-24 sm:w-12"/></a>
          <a target="_blank" href="https://t.me/inqoob_international"><IconTasksTelegram  class="w-24 sm:w-12"/></a>
        </div>
      </div>
      <div class="text-yellow-inqoob text-36px font-bold w-2/12 flex justify-center items-center">
        $5
      </div>
    </div>
    <div class="flex flex-col items-center sm:items-start text-center sm:text-left space-y-8 sm:space-y-0 sm:flex-row justify-center py-8 sm:py-16 w-full border-opacity-10 border-b border-white">
      <div class="text-120px opacity-20 w-2/12 font-bold">
        2
      </div>
      <div class="flex flex-col w-full sm:w-8/12 justify-center">
        <div class="mb-3">Text “Hi, I subscribed to your social networks!” to the support service in telegram:</div>
        <div class="">@help_inqoob</div>
      </div>
      <div class="text-yellow-inqoob font-bold w-2/12 flex flex-col justify-center items-center text-center">
        <div class="text-36px">
          $5
        </div>
        <div class="text-sm">
          + a pass to private chats of developers 
        </div>
      </div>
    </div>
    <div class="flex flex-col items-center sm:items-start text-center sm:text-left space-y-8 sm:space-y-0 sm:flex-row justify-center py-8 sm:py-16 w-full border-opacity-10 border-b border-white">
      <div class="text-120px opacity-20 w-2/12 font-bold">
        3
      </div>
      <div class="flex flex-col w-full sm:w-8/12 justify-center">
        <div class="mb-3">Create a bot</div>
        <div class="mb-3">
          Share the project on your social networks 
        </div>
        <div>
          Send the link and write the ID of the created project
        </div>
      </div>
      <div class="text-yellow-inqoob font-bold w-2/12 flex flex-col justify-center items-center text-center">
        <div class="text-36px">
          $20
        </div>
        <div class="text-sm">
          + prioritized support
        </div>
      </div>
    </div>
    <div class="flex flex-col items-center sm:items-start text-center sm:text-left space-y-8 sm:space-y-0 sm:flex-row justify-center py-8 sm:py-16 w-full border-opacity-10 border-b border-white">
      <div class="text-120px opacity-20 w-2/12 font-bold">
        4
      </div>
      <div class="flex flex-col w-full sm:w-8/12 justify-center">
        <div class="mb-3">Leave a comment under one of the latest Facebook posts</div>
        <div class="">
          Send the link for checking
        </div>
      </div>
      <div class="text-yellow-inqoob font-bold w-2/12 flex flex-col justify-center items-center text-center">
        <div class="text-36px">
          $10
        </div>
        <div class="text-sm">
          + FUNCTION “X2”
        </div>
      </div>
    </div>
    <div class="flex flex-col items-center sm:items-start text-center sm:text-left space-y-8 sm:space-y-0 sm:flex-row justify-center py-8 sm:py-16 w-full">
      <div class="text-120px opacity-20 w-2/12 font-bold">
        5
      </div>
      <div class="flex flex-col w-full sm:w-8/12 justify-center">
        <div class="mb-3">
          Leave a comment under one of the latest posts and make a story on Instagram with a mentioned 
          <span class="text-green-inqoob">@inqoob_english</span> 
          and text 
          <span class="text-green-inqoob">“inqoob $3000”</span>
        </div>
        <div class="mb-5">
          Send the link for checking
        </div>
        <div class="flex flex-row justify-center sm:justify-start">
          <a target="_blank" href="https://instagram.com/eng_inqoob?utm_medium=copy_link"><IconTasksInstagram  class="w-24 sm:w-12"/></a>
        </div>
      </div>
      <div class="text-yellow-inqoob font-bold w-1/3 sm:w-2/12 flex flex-col justify-center items-center text-center">
        <div class="text-36px">
          $10
        </div>
        <div class="text-sm">
          + can be assigneda special rank
        </div>
      </div>
    </div>
    <div class="flex flex-row justify-center py-16 w-full border-opacity-50 border-b border-white">
      <div class="hidden sm:flex text-120px opacity-2 w-2/12 font-bold">
      </div>
      <div class="hidden sm:flex flex-col w-full sm:w-8/12 justify-center">
      </div>
      <div class="text-yellow-inqoob font-bold w-full sm:w-2/12 flex flex-col justify-center items-center text-center">
        <div class="text-36px uppercase">
          get $50
        </div>
        <div class="text-sm">
          + and take part in the $3,000 raffle
        </div>
      </div>
    </div>
    <div class="my-16 w-full text-center text-xl">
      <div>
        We'll also select the most fascinating, in our view, solution.
      </div>
      <div>
        The developer will receive $100 to the card, $100 to the account and prioritized promotion in the Inqoob Store.
      </div>
    </div>
    <div class="flex justify-center"> 
      <ModuleElementButton />
    </div>
  </div>
</template>

<style>
  .opacity-2 {
    opacity: 0.02;
  }
</style>