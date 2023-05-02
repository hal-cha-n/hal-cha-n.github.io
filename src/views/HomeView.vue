<template>
  <div class="home">
    <TopHeader/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import TopHeader from '@/components/TopHeader.vue'; // @ is an alias to /src

@Options({
  components: {
    TopHeader
  },
})
export default class HomeView extends Vue {}
</script>
