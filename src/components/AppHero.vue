
<script>
export default {
    data() {
        return {
            image: 'jumbo.jpg'
        }
    },
    methods: {
        getImagePath: function (imgPath) {
            return new URL(imgPath, import.meta.url).href
        }
    }
}
</script>


<template>
    <div class="jumbo">
        <img :src="getImagePath(`../assets/${image}`)" alt="">
    </div>
</template>

<style scoped>
div.jumbo {
    display: flex;
    justify-content: center;
    margin-top: 3rem;
}

div>img {
    width: 40%;
}
</style>