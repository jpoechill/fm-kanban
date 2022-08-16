<template>
  <div class="bg-[#F4F7FD]">
    <div class="flex justify-start">
      <!-- SIDEBAR -->
      <div class="w-[300px] border-r-[1px] border-[#E4EBFA] bg-white pt-[50px] font-bold h-screen text-[#828FA3]">
        <img src="/logo-dark.svg" class="inline px-[32px] pb-[50px]" alt="kanban logo" />
        <br />

        <div class="px-[32px] pb-[20px] text-xs tracking-[3px]">
          ALL BOARDS (3)
        </div>

        <ul class="text-[15px]">
          <li class="pl-[32px] bg-[#635FC7] text-white p-3 mr-[22px] rounded-r-full">
            <img src="/icon-board.svg" class="inline pr-[14px]" alt="kanban logo" />
            Platform Launch <br />
          </li>
          <li class="pl-[32px] p-3">
            <img src="/icon-board.svg" class="inline pr-[14px]" alt="kanban logo" />
            Marketing Plan <br />
          </li>
          <li class="pl-[32px] p-3">
            <img src="/icon-board.svg" class="inline pr-[14px]" alt="kanban logo" />
            Road Map <br />
          </li>
          <li class="pl-[32px] p-3">
            <img src="/icon-board.svg" class="inline pr-[14px]" alt="kanban logo" />
            + Create New Board
          </li>
        </ul>
      </div>


      <!-- MAIN HEADER -->
      <div class="flex flex-1 flex-col">
        <div class="flex pl-[24px] h-[96px] items-center  text-2xl font-bold border-b-[1px] border-[#E4EBFA] bg-white">
          Platform Launch
        </div>
        <div class="flex items-center text-[#828FA3] font-bold text-[18px] align-center mx-auto h-full">
          This board is empty. Create a new column to get started.
        </div>
      </div>
    </div>

  </div>
</template>


<style>
html,
body {
  font-family: 'Plus Jakarta Sans', sans-serif;
}
</style>