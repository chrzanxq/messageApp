<template>
    <div class="mt-8 sm:mx-auto sm:w-full sm:max-w-md">
      <div class="bg-white px-4 py-8 shadow sm:rounded-lg sm:px-10">
        <form class="space-y-6" >
          <InputComponent
            
            id="name"
            label="Name"
            
          />
          <InputComponent
            id="email"
            label="Email address"
            type="email"
           
          />
          <InputComponent
            id="password"
            label="Password"
            type="password"
           
          />
          <div>
            <Button  :fullWidth="true" type="submit">
             
            </Button>
          </div>
        </form>
  
        <div class="mt-6">
          <div class="relative">
            <div class="absolute inset-0 flex items-center">
              <div class="w-full border-t border-gray-300"></div>
            </div>
            <div class="relative flex justify-center text-sm">
              <span class="bg-white px-2 text-gray-500">Or continue with</span>
            </div>
          </div>
  
          <div class="mt-6 flex gap-2">
            
          </div>
        </div>
  
        <div class="flex gap-2 justify-center text-sm mt-6 px-2 text-gray-500">
          <div>
           
          </div>
          <div class="underline cursor-pointer">
            
          </div>
        </div>
      </div>
    </div>
  </template>

<script setup>
import InputComponent from '../components/InputComponent.vue';
</script>