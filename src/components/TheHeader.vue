<script>
export default {
  name: "TheHeader",
  data() {
    return {
      navLinks: [
        {
          href: "#characters",
          text: "CHARACTERS",
        },
        {
          href: "#comics",
          text: "COMICS",
        },
        {
          href: "#movies",
          text: "MOVIES",
        },
        {
          href: "#tv",
          text: "TV",
        },
        {
          href: "#games",
          text: "GAMES",
        },
        {
          href: "#collectibles",
          text: "COLLECTIBLES",
        },
        {
          href: "#videos",
          text: "VIDEOS",
        },
        {
          href: "#fans",
          text: "FANS",
        },
        {
          href: "#news",
          text: "NEWS",
        },
        {
          href: "#shop",
          text: "SHOP",
        },
      ],
    };
  },

};
</script>

<template>
  <nav class="container">
    <div class="brand">
      <!-- LOGO NAVBAR -->
      <img src="../assets/dc-logo.png" alt="" />
    </div>
    <!-- LINK NAVBAR -->
    <ul class="navbar-links">
      <li v-for="(link, i) in navLinks" :key="i">
        <a class="nav-link" :href="link.href">
          {{ link.text }}
          <div class="border-b"></div>
        </a>
      </li>
    </ul>
  </nav>
</template>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;

nav {
  height: 100%;
  display: flex;
  justify-content: space-between;
}

.brand {
  padding: 0.5rem;
}

img {
  height: 100%;
}

.navbar-links {
  display: flex;
  justify-content: center;
  align-items: center;
  list-style: none;
}

.nav-link {
  padding: 1rem;
  color: #464646;
  font-weight: bold;
  text-decoration: none;
  display: inline-block;
}

.border-b {
  border-bottom: $primary-color 2px solid;
  // position: relative;
  // top: 35px;
  display: none;
}

.nav-link:hover .border-b {
  display: block;

}

.nav-link:hover {
  color: $primary-color;
  transition: color 0.3s ease;

}
</style>
