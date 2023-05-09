<template>
    <header>
        <div class="header-background"></div>
        <img class="header-logo" src="@/../resource/halchan_logo.png">
    </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'TopHeader',
});
</script>
  

<style scoped>
header {
    position: relative;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

.header-background {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-image: url('@/../resource/header_background.jpg');
    background-size: cover;
    background-position: center center;
    filter: brightness(0.5);
    z-index: -1;
}

.header-logo {
    text-align: center;
    height: 10vh;
}
</style>