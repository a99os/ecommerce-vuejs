<template lang="">
  <Header />
  <div class="main bg-[#ECF4FF] mt-1">
    <SliderIntro />
    <Categories />
    <Salers />
    <Slider />
    <Popular />
    <Brend />
    <Shop />
    <Footer />
  </div>
</template>
<script>
import Header from "./components/Header.vue";
import SliderIntro from "./components/SliderIntro.vue";
import Salers from "./components/Salers.vue";
import Categories from "./components/Categories.vue";
import Popular from "./components/Popular.vue";
import Slider from "./components/Slider.vue";
import Brend from "./components/Brend.vue";
import Shop from "./components/Shop.vue";
import Footer from "./components/Footer.vue";
export default {
  components: {
    Header,
    Salers,
    Popular,
    Slider,
    Categories,
    SliderIntro,
    Brend,
    Shop,
    Footer,
  },
  data() {
    return {};
  },
};
</script>
<style lang=""></style>
