<template>
  <div class="bg-[#F4F7FD]">
    <div class="flex justify-start">
      <!-- SIDEBAR -->
      <div
        class="flex items-stretch min-w-[300px] border-r-[1px] border-[#E4EBFA] bg-white pt-[32px] font-bold min-h-screen text-[#828FA3]">
        <div class="flex flex-col flex-1 justify-between">
          <div>
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

          <!-- Sidebar Footer -->
          <div class="flex items-start flex-col mb-[50px] px-6">
            <div class="flex w-full justify-center rounded bg-[#F4F7FD] py-3 mb-3">
              <img src="/icon-dark-theme.svg" class="inline self-center px-4" alt="Dark Theme Icon">
              Toggle
              <img src="/icon-light-theme.svg" class="inline self-center px-4" alt="Light Theme Icon">
            </div>
            <div>
              <img src="/icon-hide-sidebar.svg" class="inline mr-2" alt="Hide Sidebar Icon">
              Hide Sidebar
            </div>
          </div>
        </div>
      </div>


      <!-- MAIN HEADER -->
      <div class="flex flex-1 flex-col">
        <div class="flex pl-[24px] h-[96px] items-center  text-2xl font-bold border-b-[1px] border-[#E4EBFA] bg-white">
          Platform Launch
        </div>

        <!-- No items -->
        <!-- <div class="flex items-center text-[#828FA3] font-bold text-[18px] align-center mx-auto h-full">
          <div class="mx-auto text-center">
            This board is empty. Create a new column to get started. <br>
            <button>+ Add New Column</button>
          </div>
        </div> -->

        <div class="flex flex-1 overflow-auto justify-start pt-[25px] bg-[#F4F7FD]">
          <div class="min-w-[280px] ml-[24px] ">
            <span class="text-xs text-[#828FA3] font-bold tracking-[3px]">
              TODO (4)
            </span>
            <div class="bg-white mt-[20px] py-[20px] p-4 rounded-lg">
              <span class="font-bold text-[15px]">Build UI for onboarding flow </span><br>
              <span class="font-bold text-[#828FA3] text-xs">
                0 of 3 substacks
              </span>
            </div>
            <div class="bg-white mt-[20px] py-[20px] p-4 rounded-lg">
              <span class="font-bold text-[15px]">Build UI for onboarding flow </span><br>
              <span class="font-bold text-[#828FA3] text-xs">
                0 of 3 substacks
              </span>
            </div>
          </div>
          <div class="min-w-[280px] ml-[24px] ">
            <span class="text-xs text-[#828FA3] font-bold tracking-[3px]">
              TODO (4)
            </span>
            <div class="bg-white mt-[20px] py-[20px] p-4 rounded-lg">
              <span class="font-bold text-[15px]">Build UI for onboarding flow </span><br>
              <span class="font-bold text-[#828FA3] text-xs">
                0 of 3 substacks
              </span>
            </div>
          </div>
          <div class="min-w-[280px] ml-[24px] ">
            <span class="text-xs text-[#828FA3] font-bold tracking-[3px]">
              TODO (4)
            </span>
            <div class="bg-white mt-[20px] py-[20px] p-4 rounded-lg">
              <span class="font-bold text-[15px]">Build UI for onboarding flow </span><br>
              <span class="font-bold text-[#828FA3] text-xs">
                0 of 3 substacks
              </span>
            </div>
          </div>
          <div class="w-[280px] ml-[24px] bg-[#EAF0FA]">
            + New Column
          </div>
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