<template>
    <div class="flappy">
        <slot></slot>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
    * {
        box-sizing: border-box;
    }
    @font-face {
        font-family: 'Pixel';
        src: url('../assets/fonts/Pixel.ttf');
    }

    .flappy {
        position: relative;
        border: 5px solid dodgerblue;
        height: 700px;
        width: 1200px;
        margin: 15px;
        background-color: deepskyblue;
        overflow: hidden;
    }
</style>
