<script setup lang="ts">
import Header from './components/Header.vue'
import ConversationPanel from './components/ConversationPanel/ConversationPanel.vue'
import InputPanel from './components/InputPanel.vue'
</script>

<template>
  <div class="h-screen fixed bottom-0 left-0 w-full flex justify-center items-end min-h-screen px-3 bg-gray-100 ">
    <div class="flex flex-col h-full justify-between pb-3 w-full">
      <div class="overflow-y-scroll h-full">
        <Header />
        <ConversationPanel />
      </div>
      <div>
        <InputPanel />
      </div>
    </div>
  </div>
</template>
