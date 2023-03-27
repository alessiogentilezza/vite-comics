<script>
export default {
  name: "TheHeader",
};
</script>

<template>
  <header>
    <nav>
      <div class="brand">
        <!-- logo -->
        <img src="../assets/dc-logo.png" alt="" />
      </div>

    <ul class="navbar-links">
      <li class="nav-link">LOREM</li>
      <li class="nav-link">LOREM</li>
      <li class="nav-link">LOREM</li>
      <li class="nav-link">LOREM</li>
        <!-- <li v-for="(link, i) in navLinks" :key="i">
                                                                    <a class="nav-link" :href="link.href">
                                                                      <i class="fas" :class="'fa-' + link.icon"></i>
                                                                      {{ link.text }}
                                                                    </a>
                                                                  </li> -->
      </ul>
    </nav>
  </header>
</template>

<style scoped>
nav {
  height: 70px;
  display: flex;
}

.brand {
  padding: 10px 0;
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
  padding: 1rem 1.5rem;
  color: #464646;
  font-weight: bold;
  text-decoration: none;
  transition: color 0.3s ease;
  display: inline-block;
}

.nav-link:hover {
  color: #0282f9;
}
</style>
