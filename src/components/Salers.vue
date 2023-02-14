<template lang="">
  <section class="salers">
    <div class="container mx-auto max-w-[1230px]">
      <div class="salers__wrapper mt-10">
        <h1
          class="capitalize font-normal text-[28px] leading-[34px] text-[#1E1E1E]"
        >
          Eng ko’p sotilgan
        </h1>
        <ul
          class="categories__list py-5 flex justify-between items-center flex-wrap gap-5"
        >
          <li
            :key="item.id"
            v-for="item in salers"
            class="group px-5 rounded-[10px] relative hover:shadow-lg duration-300 hover:shadow-[#4d5ef6] h-[390px] pt-[9px] bg-white w-[230px]"
          >
            <img src="@/assets/images/image 15.png" alt="laptop" />
            <h1
              class="text-[#0D63F3] justify-center font-normal text-[18px] leading-[22px]"
            >
              {{ item.price }}
            </h1>
            <p
              class="mt-[6px] w-40 text-[#1E1E1E] justify-center h-[51px] font-normal text-[14px] leading-[17px]"
            >
              {{ item.info }}
            </p>
            <p
              class="w-40 mt-4 text-[#6C757D] justify-center font-normal text-[14px] leading-[17px]"
            >
              {{ item.order }} ta buyurtma
            </p>
            <div class="flex justify-between items-center mt-[25px]">
              <div
                class="w-[130px] text-white h-[40px] duration-300 bg-[#0D63F3] hover:bg-[#ECF4FF] hover:text-[#0D63F3] hover:border hover:border-[#0D63F3] rounded-lg"
              >
                <a
                  href="#"
                  class="w-full h-full flex items-center justify-center"
                >
                  Sotib olish
                </a>
              </div>
              <div class="flex w-10 h-10 justify-center items-center">
                <i
                  class="bx bx-cart-alt text-3xl text-[#6C757D] cursor-pointer hover:text-[#0D63F3]"
                ></i>
              </div>
            </div>
            <div
              class="h-8 w-8 absolute top-[10px] right-[10px] flex justify-center items-center"
            >
              <i
                class="bx cursor-pointer bx-heart heart-icon text-2xl text-red-300 hover:text-red-500"
              ></i>
            </div>
            <div
              v-if="item.top"
              class="top-sale inline-block rounded absolute top-[10px] left-[10px] text-white bg-[#FF0101] py-[5px] px-[10px]"
            >
              <p class="font-normal text-[16px] leading-[19px]">Top sale</p>
            </div>
            <div
              v-if="item.new"
              class="yangilik inline-block rounded absolute top-[10px] left-[10px] text-white bg-[#EB8528] py-[5px] px-[10px]"
            >
              <p class="font-normal text-[16px] leading-[19px]">Yangilik</p>
            </div>
          </li>
        </ul>
        <div
          class="list__item h-[50px] duration-300 mt-[17px] rounded-[10px] hover:shadow-[#4d5ef6] hover:text-white text-[#1E1E1E] justify-center bg-white font-normal text-[18px] leading-[22px]"
        >
          <a href="#" class="h-full w-full flex items-center justify-center"
            >Ko'proq ko'rish</a
          >
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      salers: [
        {
          id: 1,
          img: "@/assets/images/image 64.png",
          price: "299 000 so’m",
          info: "Apple Airpods Pro simsiz quloqchin , Oq rangda",
          order: 1230,
        },
        {
          id: 2,
          img: "@/assets/images/image 64.png",
          price: "16 114 285 so'm",
          info: "Apple Macbook Pro 13 2.4 2019 Intel core i5 DDR3 8 GB SSD 256 GB",
          order: 230,
          top: true,
        },
        {
          id: 3,
          img: "@/assets/images/image 64.png",
          price: "4 234 000 so’m",
          info: "Apple watch 4",
          order: 543,
          new: true,
        },
        {
          id: 4,
          img: "@/assets/images/image 64.png",
          price: "1 340 000 so’m",
          info: "Robot - tozalagich Xiaomi Mi Robot",
          order: 876,
        },
        {
          id: 5,
          img: "@/assets/images/image 64.png",
          price: "1 345 000 so’m",
          info: "Oynali Fotoaparat Canon EOS 6D Body",
          order: 565,
          new: true,
        },
        {
          id: 6,
          img: "@/assets/images/image 64.png",
          price: "299 000 so’m",
          info: "Apple Airpods Pro simsiz quloqchin , Oq rangda",
          order: 1230,
          new: true,
        },
        {
          id: 7,
          img: "@/assets/images/image 64.png",
          price: "16 114 285 so'm",
          info: "Apple Macbook Pro 13 2.4 2019 Intel core i5 DDR3 8 GB SSD 256 GB",
          order: 230,
        },
        {
          id: 8,
          img: "@/assets/images/image 64.png",
          price: "4 234 000 so’m",
          info: "Apple watch 4",
          order: 543,
        },
        {
          id: 9,
          img: "@/assets/images/image 64.png",
          price: "1 340 000 so’m",
          info: "Robot - tozalagich Xiaomi Mi Robot",
          order: 876,
          top: true,
        },
        {
          id: 10,
          img: "@/assets/images/image 64.png",
          price: "1 345 000 so’m",
          info: "Oynali Fotoaparat Canon EOS 6D Body",
          order: 565,
        },
      ],
    };
  },
};
</script>
<style lang=""></style>
