<template>
  <div class="container">
      <div class="video-player">
          <video ref="video" class="video">
              <source src="../assets/videoplayback.mp4" type="video/mp4">
          </video>
      </div>
  </div>
</template>

<script>
export default {
    name: "video",

}
</script>

<style scoped>
.container {
    display: flex;
    justify-content: center;
    width: auto;
    height: auto;
    margin: 70px;
}
</style>