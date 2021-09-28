<template>
    <div class="hero">
        <img :src="imgFile" class="hero__img">
    </div>
</template>

<script>
export default {
    name: 'Hero',
    props: {
        imgFile: String
  }
}
</script>

<style scoped>
    .hero {
        position: absolute;
        top: 0;
        z-index:-1;
        width: 100%;
        height: 100vh;
        background-color: lightyellow;
        overflow: hidden;
    }
    
    .hero__img {
        mix-blend-mode: multiply;
        width: 100%;
        height: 100%;
        object-fit: contain;
        object-position: center;

    }

</style>