<script>
export default {
  name: "TheFooter",
};
</script>

<template>
  <div class="footer-top container">
    <div class="menu">

      <div class="col">
        <h3>DC COMICS</h3>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>Tv</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <h3>SHOP</h3>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>

      </div>
      <div class="col">
        <h3>DC </h3>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>Tv</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>Tv</li>
        </ul>
      </div>

      <div class="col">
        <h3>SITE </h3>
        <ul>
          <li>DC News</li>
          <li>DC Characters</li>
          <li>DC Comics</li>
          <li>DC Movies</li>
          <li>DC Tv</li>
        </ul>
      </div>

    </div>
    <img src="../assets/dc-logo-bg.png" alt="">
  </div>
</template>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;

.footer-top {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  overflow-y: hidden;
}

.menu {
  color: white;
  display: flex;
  width: 40%;
}

.col {
  width: calc(100% / 3);
  font-size: small;
}

.col ul li {
  list-style: none;
  color: $text-color;
  padding: 0.2rem 0;
}

.col ul li:hover {
  color: white;
  cursor: pointer;
}

h3 {
  color: white;
  padding: 1rem 0;
}

img {
  height: 150%;
}
</style>
