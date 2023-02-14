<template lang="">
  <section class="shop">
    <div class="container mx-auto w-[1230px]">
      <div class="shop__wrapper mt-[60px] pb-20">
        <h1
          class="capitalize font-normal text-[28px] leading-[34px] text-[#1E1E1E]"
        >
          Do’konlarimiz
        </h1>
        <ul class="flex gap-5 mt-5 flex-wrap">
          <li
            v-for="item in shops"
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
      shops: [
        { id: 1, img: "/src/assets/images/image11.png" },
        { id: 2, img: "/src/assets/images/image12.png" },
        { id: 3, img: "/src/assets/images/image13.png" },
        { id: 4, img: "/src/assets/images/image14.png" },
        { id: 5, img: "/src/assets/images/image15.png" },
        { id: 6, img: "/src/assets/images/image9.png" },
        { id: 7, img: "/src/assets/images/image9.png" },
        { id: 8, img: "/src/assets/images/image9.png" },
        { id: 9, img: "/src/assets/images/image9.png" },
        { id: 10, img: "/src/assets/images/image9.png" },
        { id: 11, img: "/src/assets/images/image9.png" },
        { id: 12, img: "/src/assets/images/image9.png" },
      ],
    };
  },
};
</script>
<style lang=""></style>
