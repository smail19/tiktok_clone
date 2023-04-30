<script setup>
const route= useRoute()

</script>
<template>
    <div class="fixed bg-white z-30 flex items-center w-full border-b h-[61px]">
        <div
         :class="route.fullPath ==='/' ? 'max-w-[1150px]' : ''"
         class="flex items-center  justify-between w-full px-6 mx-auto">
              <div :class="route.fullPath ==='/' ? 'w-[80%]' : 'lg:w-[20%] w-[70%]'">
                <NuxtLink to="/">
                    <img width="115" src="assets/images/tiktok-logo.png"> 
                </NuxtLink>
              </div>
        </div>
    </div>
</template>


