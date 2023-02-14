<template lang="">
  <section class="slider">
    <div class="container max-w-[1230px] mx-auto">
      <div class="slider__wrapper pt-10 relative">
        <img src="@/assets/images/Frame 2 (1).png" alt="slider img" />
        <div
          class="btn-slider cursor-pointer left-arrow absolute w-[42px] h-[42px] rounded-full flex items-center justify-center -left-[62px] top-1/2"
        >
          <i class="bx bx-chevron-left text-2xl"></i>
        </div>
        <div
          class="btn-slider cursor-pointer right-arrow absolute w-[42px] h-[42px] rounded-full flex items-center justify-center -right-[62px] top-1/2"
        >
          <i class="bx bx-chevron-right text-2xl"></i>
        </div>
        <div class="mt-[20px] w-[150px] mx-auto flex justify-between">
          <div
            class="btn-slider btn-slider__active h-4 w-4 rounded-full duration-300"
          ></div>
          <div class="btn-slider h-4 w-4 rounded-full duration-300"></div>
          <div class="btn-slider h-4 w-4 rounded-full duration-300"></div>
          <div class="btn-slider h-4 w-4 rounded-full duration-300"></div>
          <div class="btn-slider h-4 w-4 rounded-full duration-300"></div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style lang=""></style>
