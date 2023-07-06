<template>
  <div class="ml-[420px] w-full">
    <div class="w-full">
      <div class="border-l border-green-500 w-full">
        <div
          class="bg-gray-100 fixed z-10 min-w-[calc(100vw-420px)] flex justify-between items-center px-2 py-2"
        >
          <div class="flex items center">
            <img
              class="rounded-full mx-1 w-10"
              src="https://random.imagecdn.app/100/100"
              alt=""
            />
            <div class="text-gray-900 ml-1 font-semibold">Frank</div>
          </div>
          <DotsHorizontalIcon fillColor="#515151" class="mr-6" />
        </div>
      </div>
      <div id="MessagesSection"></div>
      <div class="w-[calc(100vw-420px)] p-2.5 z-10 bg-[#F0F0F0] fixed bottom-0">
                <div class="flex items-center justify-center">
                    <EmoticonExcitedOutlineIcon :size="27" fillColor="#515151" class="mx-1.5" />
                    <Paperclip :size="27" fillColor="#515151" class="mx-1.5 mr-3" />
                    <input 
                    
                    class="
                        mr-1
                        shadow
                        apperance-none
                        rounded-lg
                        w-full
                        py-3
                        px-4
                        text-gray-700
                        leading-tight
                        focus:outline-none 
                        focus:shadow-outline
                    "
                    autocomplete="off"
                    type="text"
                    placeholder="Message"
                    >

                    <button 
                        
                        class="ml-3 p-2 w-12 flex items-center justify-center"
                    >
                        <SendCircleOutline fillColor="#515151" />
                    </button>
                </div>
            </div>
    </div>
  </div>
</template>

<script setup>
import DotsHorizontalIcon from "vue-material-design-icons/DotsHorizontal.vue";
import EmoticonExcitedOutlineIcon from "vue-material-design-icons/EmoticonExcitedOutline.vue";
import Paperclip from "vue-material-design-icons/Paperclip.vue";
import SendCircleOutline from 'vue-material-design-icons/SendCircleOutline.vue'
</script>

<style lang="scss" scoped>
</style>