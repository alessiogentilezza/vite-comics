<script>
export default {
    name: "BannerBlu",
};
</script>

<template>
    <nav>
        <ul class="navbar-links">
            <li class="nav-link"> <img src="../assets/buy-comics-digital-comics.png" alt="" />
                LOREM</li>
            <li class="nav-link"> <img src="../assets/buy-comics-merchandise.png" alt="" />
                LOREM</li>
            <li class="nav-link"> <img src="../assets/buy-comics-subscriptions.png" alt="" />
                LOREM</li>
            <li class="nav-link"> <img src="../assets/buy-comics-shop-locator.png" alt="" />
                LOREM</li>
            <li class="nav-link"> <img src="../assets/buy-dc-power-visa.svg" alt="" />
                LOREM</li>
        </ul>
    </nav>
</template>

<style scoped>
img {
    height: 100%;
    padding: 1rem;
}

nav {
    height: 100%;
    display: flex;
}

.navbar-links {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style: none;

}

.nav-link {
    height: 100%;
    padding: 1rem;
    color: white;
    font-weight: bold;
    text-decoration: none;
    display: flex;
    align-items: center;
}
</style>
