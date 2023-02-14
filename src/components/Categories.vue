<template lang="">
  <section class="categories">
    <div class="container mx-auto max-w-[1230px]">
      <h1
        class="capitalize font-normal text-[28px] leading-[34px] text-[#1E1E1E]"
      >
        Kategoriyalar
      </h1>
      <ul class="categories__list py-5 flex justify-between items-center">
        <li
          :key="item.id"
          v-for="item in categories"
          class="list__item group rounded-[10px] shadow-lg hover:shadow-lg duration-300 hover:shadow-[#4d5ef6] h-[200px] pt-[9px] bg-white w-[136px]"
        >
          <a href="#">
            <img
              :src="item.img"
              :alt="item.name"
              class="mt-[9px]"
              alt="apple"
            />
            <p
              class="font-normal group-hover:text-white text-[14px] leading-[17px] text-[#1E1E1E] text-center mx-auto"
            >
              {{ item.name }}
            </p>
          </a>
        </li>
      </ul>
      <div
        class="list__item h-[50px] duration-300 rounded-[10px] hover:shadow-[#4d5ef6] hover:text-white text-[#1E1E1E] justify-center bg-white font-normal text-[18px] leading-[22px]"
      >
        <a href="#" class="h-full w-full flex items-center justify-center"
          >Batafsil</a
        >
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      categories: [
        { id: 1, name: "Smartfonlar", img: "/src/assets/images/image 61.png" },
        {
          id: 2,
          name: "Kompyuterlar va notebooklar",
          img: "/src/assets/images/image 62.png",
        },
        { id: 3, name: "Televizorlar", img: "/src/assets/images/image 63.png" },
        {
          id: 4,
          name: "Aqlli soatlar",
          img: "/src/assets/images/image 64.png",
        },
        { id: 5, name: "Quloqchinlar", img: "/src/assets/images/image 65.png" },
        { id: 6, name: "Konditsioner", img: "/src/assets/images/image 66.png" },
        { id: 7, name: "Sovutkichlar", img: "/src/assets/images/image 67.png" },
        {
          id: 8,
          name: "Kir yuvish mashinalari",
          img: "/src/assets/images/image 68.png",
        },
      ],
    };
  },
};
</script>
<style lang=""></style>
