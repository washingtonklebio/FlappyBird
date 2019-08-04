<template>
    <div class="pipe">
        <div class="body"></div>
        <div class="edge"></div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .pipe {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .pipe .edge {
        height: 30px;
        width: 130px;
        background: linear-gradient(90deg, #639301, #A5E82E);
        border: 2px solid #000;
    }

    .pipe .body {
        height: 40px;
        width: 110px;
        background: linear-gradient(90deg, #639301, #A5E82E);
        border-left: 2px solid #000;
        border-right: 2px solid #000;
    }
</style>
