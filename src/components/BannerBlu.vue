<script>
export default {
    name: "BannerBlu",
    data() {
        return {
            cards: [
                {
                    text: "DIGITAL COMICS",
                    path: "buy-comics-digital-comics.png",
                },
                {
                    text: "DC MERCHANDISE",
                    path: "buy-comics-merchandise.png",
                },
                {
                    text: "SUBSCRIPTIONS",
                    path: "buy-comics-subscriptions.png",
                },
                {
                    text: "COMIC SHOP-LOCATOR",
                    path: "buy-comics-shop-locator.png",
                },
                {
                    text: "DC-POWER-VISA",
                    path: "buy-dc-power-visa.svg",
                }
            ],
        };
    },
    methods: {
        getImagePath: function (img) {
            return new URL(`../assets/${img}`, import.meta.url).href;
        }
    }
};

</script>

<template>
    <nav class="container">
        <ul class="navbar-links">
            <!-- CARD NAVBAR -->
            <li class="nav-link" v-for="(card, index) in cards" :key="index">
                <img :src="getImagePath(card.path)" alt="">
                {{ card.text }}
            </li>
        </ul>
    </nav>
</template>

<style scoped>
img {
    height: 60px;
    padding: 0.5rem;
}

img:hover {
    height: 80px;
    transition: all 0.3s;
}

nav {
    height: 100%;
}

.navbar-links {
    height: 100%;
    display: flex;
    justify-content: space-between;
}

.nav-link {
    height: 100%;
    color: white;
    display: flex;
    align-items: center;
}
</style>
