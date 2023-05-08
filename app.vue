<template>
  <div :class="{'dark': darkMode}">
    <div class="bg-white dark:bg-dim-900">
    <div class="min-h-full ">
      <div class="grid grid-cols-12 mx-auto sm:px-0 lg:max-w-7xl lg:px-7 lg:gap-0">
        <!-- Left side bar-->
        <div class="hidden md:block xs-col-span-1 xl:col-span-2">
          <div class="sticky top-0">
            <SidebarLeft/>
          </div>
        </div>
        <!-- Main Content-->
        <main class="col-span-12 md:col-span-8 xl:col-span-6">
            <h1>Asd</h1>
        </main>
        <!-- Right side bar-->
        <div class="hidden col-span-12 md:block xl:col-span-4 md:col-span-3">
          <div class="sticky top-0">
            <SidebarRight/>
          </div>
        </div>


      </div>
    </div>
  </div>
  </div>
</template>

<script setup>
  const darkMode = ref(false)
</script>
