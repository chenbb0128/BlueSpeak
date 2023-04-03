<script lang="ts" setup>
import LanguageSelector from './LanguageSelector.vue'
</script>

<template>
  <div class="flex flex-col sm:pt-16 sticky pt-12">
    <img class="w-12 h-12 ml-2" src="@/assets/img/logoIcon.svg" alt="">
    <div class="flex flex-row py-2 justify-between items-center w-full">
      <span class="font-bold text-2xl ml-2 text-transparent bg-clip-text bg-gradient-to-r from-blue-500  to-green-300">
        BlueSpeak
      </span>
      <LanguageSelector />
    </div>
  </div>
</template>
