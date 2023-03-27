<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";

export default {
  components: {
    TheHeader,
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

  </section>
  <footer>
    <TheFooter class="container"></TheFooter>

  </footer>
  <section id="gray">

  </section>
</template>

<style>
header {
  height: 70px;
}

main {
  height: 70px;
  background-color: black;
  display: flex;
  align-items: center;
}

#blue {
  height: 100px;
  background-color: #0282f9;
}

#gray {
  height: 70px;
  background-color: #303030;
}

footer {
  height: 350px;
  background-image: url(./assets/footer-bg.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}

.container {
  max-width: 80%;
}

h1 {
  color: white;
}
</style>
