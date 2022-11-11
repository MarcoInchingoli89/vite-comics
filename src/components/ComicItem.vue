<script>
export default {
    name: 'ComicItem',
    props: {
        image: String,
        name: String
    },
}

</script>

<template>
    <div class="col-2">
        <img class="py-2 px-3" width="100" :src="image" alt="">
        <h3 class="text_white px-3">{{ name }}</h3>
    </div>
</template>

<style scoped>
.text_white {
    color: white;
    font-size: 0.9rem;
    text-transform: uppercase;
}
</style>