<script>
import TheHeader from "./components/TheHeader.vue";
import BannerBlu from "./components/BannerBlu.vue";
import TheFooter from "./components/TheFooter.vue";
import BannerGray from "./components/BannerGray.vue";

export default {
  components: {
    TheHeader,
    BannerBlu,
    TheFooter,
    BannerGray,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<template>
  <header>
    <TheHeader></TheHeader>

  </header>
  <main>
    <div class="container">
      <h1> -- WORK IN PROGRESS -- </h1>
    </div>

  </main>
  <section id="blue">
    <BannerBlu></BannerBlu>


  </section>
  <footer>
    <TheFooter></TheFooter>

  </footer>
  <section id="gray">
    <BannerGray></BannerGray>


  </section>
</template>

<style lang="scss">
@use "./styles/general.scss";
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');
</style>
