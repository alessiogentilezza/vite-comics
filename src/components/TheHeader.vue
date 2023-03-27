<script>
export default {
  name: "TheHeader",
};
</script>

<template>
  <nav>
    <div class="brand">
      <!-- logo -->
      <img src="../assets/dc-logo.png" alt="" />
    </div>

    <ul class="navbar-links">
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
        <div class="border-b"></div>
      </li>
      <li class="nav-link">LOREM
      <div class="border-b"></div>
    </li>
    <li class="nav-link">LOREM
      <div class="border-b"></div>
    </li>
      <!-- <li v-for="(link, i) in navLinks" :key="i">
                                                                                                                            <a class="nav-link" :href="link.href">
                                                                                                                              <i class="fas" :class="'fa-' + link.icon"></i>
                                                                                                                              {{ link.text }}
                                                                                                                            </a>
                                                                                                                          </li> -->
    </ul>
  </nav>
</template>

<style scoped>
nav {
  height: 100%;
  display: flex;
}

.brand {
  padding: 1rem;
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
}

.border-b {
  border-bottom: #0282f9 2px solid;
  display: none;
}

.nav-link:hover .border-b {
  display: block;
}

.nav-link:hover {
  color: #0282f9;
}
</style>
