<template>
    <div class="area">
        <slot></slot>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .area {
        position: absolute;
        top: 0;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
</style>
