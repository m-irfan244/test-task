<template>
  <footer>
    <div class="container">
      <div class="left">
        <p class="copyright">&#169; Copyright 2021 All Rights Reserved</p>
      </div>
      <div class="right">
        <router-link class="footer-link" to="#">Privacy Policy</router-link>
        <span class="line">|</span>
        <router-link class="footer-link" to="#">Terms of Service</router-link>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
    name: "Footer",

};
</script>

<style scoped>
footer {
  margin-top: auto;
  background-color: #000;
  padding: 5px 20px;
  height: 50px;
}

.container{
    background-color: black;
    color: white;
    padding:10px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.left {

  text-decoration: none;
}

.footer-link {
  padding: 0 10px;
  text-decoration: none;
}

.footer-link:hover {
    color: #f9f9f9;
}
.copyright {
  color: #fff;
  text-decoration: none;
}
</style>