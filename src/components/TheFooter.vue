<script>
export default {
  name: "TheFooter",
};
</script>

<template>
  <div class="footer-top">
    <div class="menu">
      <div class="col">
        <h3>DC COMICS</h3>
        <ul>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
        </ul>
        <h3>SHOP</h3>
        <ul>
          <li>lorem</li>
          <li>lorem</li>
        </ul>

      </div>
      <div class="col">
        <h3>DC </h3>
        <ul>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
        </ul>
      </div>
      <div class="col">
        <h3>SITE </h3>
        <ul>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
        </ul>
      </div>
    </div>
    <img src="../assets/dc-logo-bg.png" alt="">

  </div>
</template>

<style scoped>
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
}

.col ul li {
  list-style: none;
  color: #959595;
  padding: 0.5rem 0;
}

h3 {
  color: white;
}
</style>
