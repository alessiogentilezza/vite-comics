<script>
export default {
  name: "TheFooter",
};
</script>

<template>
  <div class="footer-top">
    <div class="menu">
      <div class="col">
        <ul>
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
  margin: 0;
}

img {
  margin: 0;
}

.col {
  width: calc(100% / 3);
}

.col ul li {
  list-style: none;
  color: #959595;
  padding: 10px 0;
}
</style>
