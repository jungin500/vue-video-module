<template lang="html">
    <div class="app-container">
        <router-view></router-view>
    </div>
</template>

<script>
    export default {};
</script>

<style lang="scss">
    @import "../style/mixin";
    @import url('https://fonts.googleapis.com/icon?family=Material+Icons');
    @font-face {
        font-family: 'NanumBarunGothic';
        src: url('../font/NanumBarunGothic.eot') format('eot');
        src: url('../font/NanumBarunGothic.ttf') format('ttf');
        src: url('../font/NanumBarunGothic.woff') format('woff');
    }
    html,
    body {
        position: relative;
        width: 100%;
        height: 100%;
        overflow-x: hidden;
        margin: 0;
        padding: 0;
        border: 0;
    }
    
    #app,
    .app-container {
        position: relative;
        width: 100%;
        height: 100%;
        min-width: 768px;
    }
</style>
