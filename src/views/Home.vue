<template>
  <div class="home">
    <Blogpost />
    <Video class="video" />
  </div>
</template>

<script>
// @ is an alias to /src
import Blogpost from '../components/Blogpost.vue';
import Video from '../components/Video.vue'

export default {
  name: 'Home',
  components: {
    Blogpost,
    Video
  },
}
</script>

<style scoped>

</style>