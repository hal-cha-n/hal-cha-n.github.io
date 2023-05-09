<template>
  <div class="home">
    <TopHeader />

    <div class="container-fluid">
      <ProfileSection />
      <YouTubeSection />
    </div>
    <YouTubeModal />

    <TopFooter />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import TopHeader from '@/components/TopHeader.vue'; // @ is an alias to /src
import ProfileSection from '@/components/ProfileSection.vue'; // @ is an alias to /src
import YouTubeSection from '@/components/YouTubeSection.vue'; // @ is an alias to /src
import YouTubeModal from '@/components/YouTubeModal.vue'; // @ is an alias to /src
import TopFooter from '@/components/TopFooter.vue'; // @ is an alias to /src

@Options({
  components: {
    TopHeader, ProfileSection, YouTubeSection, YouTubeModal, TopFooter
  },
})
export default class HomeView extends Vue { }
</script>
