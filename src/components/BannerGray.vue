<script>
export default {
    name: "BannerGray",
};
</script>

<template>
    <div class="container-small">
        <button>SIGN-UP NOW!</button>

        <div class="dx"> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores, itaque!</div>
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
</style>
