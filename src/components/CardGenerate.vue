<script>
export default {
    name: "CardGenerate",
    props: {
        image: String,
        title: String,
        genere: String
    }
};
</script>

<template>
    <div class="container">
        <div class="product-card">
            <img :src="image" :alt="title" />
            <h3>{{ title }}</h3>
            <h4>{{ genere }}</h4>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;

.product-card {
    & img {
        width: 100%;
    }
}

h4 {
    color: $primary-color;
}
</style>