<template>
    <div class="flex">
        <div id="Header" class="fixed w-[420px] z-10">
            <div class="bg-gray-100 w-full flex justify-between">
                <img class="rounded-full ml-1 w-10" src="https://random.imagecdn.app/100/100" alt="">
                <div class="flex items-center justify-center">
                    <AccountGroupOutline fillColor="#515151" class="mr-6" />
                    <DotsHorizontalIcon fillColor="#515151" class="mr-6" />
                </div>
            </div>
            <div id="Search" class="bg-white w-full px-2 border-b shadow-md">
                <div class="px-1 m-2 bg-gray-100 w-full flex justify-between rounded-md">
                    <MagnifyIcon fillColor="#515151" :size="18" class="ml-2" />
                    <input type="text" class="
                     ml-5
                     apperance-none
                     w-full
                     bg-gray-100
                     py-1.5
                     px-2.5
                     text-gray-800
                     leading-light
                     focus:outline-none
                     focus:shadow-outline
                     placeholder:text-sm
                     placeholder:text-gray-500
                     " autocomplete="off" placeholder="Start a new chat">
                </div>
            </div>
        </div>
        <ChatsView class="mt-[100px]" />

        <div class="ml-[420px] fixed w-[calc(100vw-420px)] h-[100vh] bg-gray-100 text-center">
            <div class="w-full flex items-center justify-center">
                <div class="grid h-screen place-items-center">

                <div class="w-full flex items-center justify-center">
                    <img width="375" src="https://random.imagecdn.app/400/200" alt="">
                </div>
                <div class="text-[32px] text-gray-500 font-light mt-10">MessageApp Web</div>
                <div class="text-[14px] text-gray-600 mt-2">
                    <div>Send And Receive messages without keeping your phone online</div>
                    <div>Use MessagApp on up to 4 linked devices and 1 phone at the same time</div>
                </div>
                </div>

            </div>
        </div>


    </div>
</template>

<script setup>
import ChatsView from './ChatsView.vue'

import AccountGroupOutline from 'vue-material-design-icons/AccountGroupOutline.vue'
import DotsHorizontalIcon from 'vue-material-design-icons/DotsHorizontal.vue'
import MagnifyIcon from 'vue-material-design-icons/Magnify.vue'

</script>

<style lang="scss" scoped></style>
