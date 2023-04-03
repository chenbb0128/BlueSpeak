<template>
  <div class="flex flex-col items-start justify-center space-y-2">
    <div class="flex flex-row items-center space-x-2">
      <img class="w-6 h-6 text-gray-800" src="@/assets/img/tipsIcon.svg" alt="">
      <span class="text-xl font-medium text-gray-800">小提示</span>
    </div>
    <div class="text-gray-800 leading-7 flex flex-row space-x-2">
      <img class="w-5 h-5 text-gray-800 shrink-0" src="@/assets/img/rightTriangleIcon.svg" alt="">
      <div>
        <span className="border w-min inline py-0.5 px-2 border-gray-700 rounded-md">
          Shift
        </span>
        &nbsp;+
        <span className="border w-min inline py-0.5 px-2 border-gray-700 rounded-md">
          Enter
        </span>
        &nbsp;换行。
        <span className="border w-min inline py-0.5 px-2 border-gray-700 rounded-md">
          Enter
        </span>
        &nbsp; 发送消息。
      </div>
    </div>
  </div>
</template>
