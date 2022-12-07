<template>
  <div>
    <div class="w-full flex items-center justify-between">
      <div class="bg-red-100 w-64 h-64"></div>
      <div class="bg-red-500 w-64 h-64 flex-grow"></div>
      <div class="bg-red-700 w-64 h-64"></div>
    </div>
    <div class="w-full h-64 bg-blue-400 relative">
        <!-- 定位居中 -->
        <div class="absolute w-20 h-20 bg-red-900 top-0 right-0 left-0 bottom-0 m-auto"></div>
    </div>
    <div class="w-full h-64 bg-blue-700 relative opacity-10 md:opacity-50">
        <!-- 定位居中 -->
        <div class="absolute w-20 h-20 bg-red-900 opacity-50 top-0 right-0 left-0 bottom-0 m-auto border-2 border-yellow-600 rounded-20px"></div>
    </div>
    <div class="w-full h-64 bg-main border-2 border-red-800 rounded-md">
        <div class="w-20 h-20 bg-red-200 hover:bg-black cursor-pointer shadow-lg"></div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "testDemo",
  components: {},
};
</script>