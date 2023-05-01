<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    <MyButton label="Click me!" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import MyButton from '@/components/MyButton.vue'; // @ is an alias to /src

@Options({
  components: {
    HelloWorld, MyButton
  },
})
export default class HomeView extends Vue {}
</script>
