<template>
  <div class="flex bg-gray-100">
    <!-- LEFT DIV -->
    <div class="px-8 py-12 max-w-md mx-auto sm:max-w-xl lg:max-w-full lg:w-1/2 lg:py-24 lg:px-12">
        <div class="xl:max-w-lg xl:ml-auto">
            <img class="h-10" src="img/logo.svg" alt="Workcation">
            <img src="img/beach-work.jpg" alt="Woman workcation"
                class="mt-6 rounded-lg sm:mt-8 sm:h-64 sm:w-full sm:object-cover sm:object-center shadow-xl lg:hidden">
            <h1
                class="mt-6 text-2xl font-semibold text-gray-900 leading-tight sm:mt-8 sm:text-4xl lg:text-3xl xl:text-4xl">
                You
                can
                work from
                anywhere. <br /><span class="text-indigo-400">Take advantage of it.</span>
            </h1>
            <p class="mt-2 text-gray-600 sm:mt-4 sm:text-xl">Workcation helps you find work-friendly rentals in
                beautiful locations</p>
            <div class="mt-4 sm:mt-6">
                <button class="btn btn-indigo shadow-lg sm:text-base"><a href="#">Book your escape</a></button>
                <button class="btn btn-gray ml-2 sm:text-base"><a href="#">Learn more</a></button>
            </div>
        </div>
    </div>

    <!-- RIGHT DIV -->
    <div class="hidden lg:block lg:w-1/2 lg:relative">
        <img src="img/beach-work.jpg" alt="Woman workcation"
            class="absolute inset-0 h-full w-full object-cover object-center">
    </div>
    </div>
</template>

<script>
export default {}
</script>
