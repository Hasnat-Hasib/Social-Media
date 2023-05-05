<template>
  <div :class="{'dark': darkMode}">
    <div class="bg-white dark:bg-dim-900">
    <div class="min-h-full ">
      <div class="grid grid-cols-12 mx-auto sm:px-0 lg:max-w-7xl lg:px-7 lg:gap-0">
        <!-- Left side bar-->
        <div class=" md:block xs-col-span-1 xl:col-span-2">
          <div class="sticky top-0">
            <SidebarLeft/>

          </div>

        </div>
        <!-- Main Content-->
        <!-- Right side bar-->


      </div>
    </div>
  </div>
  </div>
</template>

<script setup>
  const darkMode = ref(false)
</script>
