<template lang="">
  <header class="shadow-md shadow-[#00000038]">
    <div class="container max-w-[1230px] mx-auto">
      <div class="flex justify-end mb-[6px] h-[30px] items-center">
        <div>
          <i class="bx bxs-envelope"></i>
          <a href="#" class="ml-[10px]">Aloqa uchun</a>
        </div>
        <div>
          <p class="inline-block ml-[221px]">UZ</p>
          <i class="bx bx-chevron-down ml-[9px]"></i>
        </div>
      </div>
      <nav class="flex h-[70px] items-center">
        <a href="#" class="">
          <img
            src="@/assets/images/Logo.svg"
            class="w-[91px] h-[35px]"
            alt="logo"
          />
        </a>
        <div
          class="w-[149px] h-[46px] rounded-lg btn-katalog duration-300 border ml-[117px] flex justify-center items-center hover:border-[#4d5ef6] cursor-pointer"
        >
          <a href="#" class="flex justify-center items-center">
            <i class="bx bx-menu text-xl text-white"></i>
            <p
              class="uppercase text-4 leading-[19px] ml-[15px] text-white font-normal"
            >
              Katalog
            </p>
          </a>
        </div>
        <div class="flex ml-[60px]">
          <input
            type="text"
            placeholder="Maxsulotlarni izlash"
            class="border rounded-l-lg pl-[18px] w-[336px] text-[#0D63F3] outline-[#0D63F3] hover:border hover:border-[#0D63F3] placeholder:text-4 placeholder:leading-[19px] placeholder:font-normal"
          />
          <div
            class="icon w-[60px] h-[46px] bg-[#0D63F3] cursor-pointer border flex items-center justify-center rounded-r-lg hover:bg-[#ECF4FF] hover:border-[#0D63F3]"
          >
            <i class="bx bx-search-alt-2 text-white text-xl"></i>
          </div>
        </div>

        <div
          class="heart-icon group h-[46px] w-[46px] flex justify-center items-center bg-[#ECF4FF] rounded-lg ml-[81px] cursor-pointer duration-300 hover:bg-[#0D63F3]"
        >
          <i
            class="bx bx-heart group-hover:text-[#ECF4FF] text-2xl text-[#0D63F3]"
          ></i>
        </div>
        <div
          class="cart-icon group h-[46px] w-[46px] flex justify-center items-center bg-[#ECF4FF] rounded-lg ml-20 cursor-pointer duration-300 hover:bg-[#0D63F3]"
        >
          <i
            class="bx bx-cart-alt group-hover:text-[#ECF4FF] text-2xl text-[#0D63F3]"
          ></i>
        </div>
        <div
          class="w-[105px] rounded-lg h-[46px] btn-katalog duration-300 border ml-[59px] flex justify-center items-center hover:border-[#4d5ef6] cursor-pointer"
        >
          <a href="#" class="flex justify-center items-center">
            <p class="text-4 leading-[19px] text-white font-normal">Kirish</p>
          </a>
        </div>
      </nav>
    </div>
  </header>
</template>
<script>
export default {};
</script>
<style lang=""></style>
