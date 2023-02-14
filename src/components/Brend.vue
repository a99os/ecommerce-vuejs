<template lang="">
  <section class="brend">
    <div class="container mx-auto w-[1230px]">
      <div class="brend__wrapper mt-[60px]">
        <h1
          class="capitalize font-normal text-[28px] leading-[34px] text-[#1E1E1E]"
        >
          Brendlar bo'yicha
        </h1>
        <ul class="flex gap-5 mt-5 flex-wrap">
          <li
            v-for="item in brends"
            class="py-[5px] px-[49px] rounded-lg bg-white hover:shadow-lg hover:shadow-[#4d5ef6] cursor-pointer"
          >
            <img :src="item.img" class="w-[90px] h-[90px]" alt="" />
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      brends: [
        { id: 1, img: "/src/assets/images/image1.png" },
        { id: 2, img: "/src/assets/images/image2.png" },
        { id: 3, img: "/src/assets/images/image3.png" },
        { id: 4, img: "/src/assets/images/image4.png" },
        { id: 5, img: "/src/assets/images/image5.png" },
        { id: 6, img: "/src/assets/images/image6.png" },
        { id: 7, img: "/src/assets/images/image7.png" },
        { id: 8, img: "/src/assets/images/image8.png" },
        { id: 9, img: "/src/assets/images/image9.png" },
        { id: 10, img: "/src/assets/images/image9.png" },
        { id: 11, img: "/src/assets/images/image9.png" },
        { id: 12, img: "/src/assets/images/image9.png" },
        { id: 13, img: "/src/assets/images/image9.png" },
        { id: 14, img: "/src/assets/images/image9.png" },
        { id: 15, img: "/src/assets/images/image9.png" },
      ],
    };
  },
};
</script>
<style lang=""></style>
