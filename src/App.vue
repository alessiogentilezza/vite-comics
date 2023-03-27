<script>
import TheHeader from "./components/TheHeader.vue";
import BannerBlu from "./components/BannerBlu.vue";
import TheFooter from "./components/TheFooter.vue";

export default {
  components: {
    TheHeader,
    BannerBlu,
    TheFooter,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<template>
  <header>
    <TheHeader class="container"></TheHeader>

  </header>
  <main>
    <div class="container">
      <h1> -- WORK IN PROGRESS -- </h1>
    </div>

  </main>
  <section id="blue">
    <BannerBlu class="container"></BannerBlu>


  </section>
  <footer>
    <TheFooter class="container"></TheFooter>

  </footer>
  <section id="gray">

  </section>
</template>

<style></style>
