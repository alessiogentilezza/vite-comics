<script>
export default {
    name: "BannerGray",
};
</script>

<template>
    <div class="container-small">
        <button>SIGN-UP NOW!</button>
        <div class="dx">
            <div>FOLLOWS US</div>
            <div>
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped>
.container-small {
    height: 100%;
    display: flex;
    color: white;
    justify-content: space-between;
    align-items: center;
}

button {
    border: 2px solid #0282f9;
    padding: 0.5rem 1rem;
    font-size: 1em;
    font-weight: 500;
    font-family: inherit;
    background-color: transparent;
    cursor: pointer;
    transition: border-color 0.25s;
    color: white;
}

.dx {
    height: 100%;
    display: flex;
    color: #117cf9;
    justify-content: space-between;
    align-items: center;
}

.dx img {
    padding: 0 .7rem;
}
</style>
