<template>
  <div class="blog-wrapper">
    <div class="blog-content">
      <div class="blog-left">
        <h2>Welcome!</h2>
        <p>
          Before we dive into rates, let's take a look at which insurance
          company would be the best recommendation based on underwriting
          criteria. Please choose your application type.
        </p>
        <hr />
        <div class="boxes">
          <router-link class="UW-links terms" to="#">UW-terms+</router-link>
          <router-link class="UW-links swli" to="#">UW-SWLI</router-link>
        </div>
      </div>
      <div class="blog-right">
        <img
          src="https://www.pngmagic.com/product_images/dark-blue-website-background-images.jpg"
          alt=""
        />
        <div class="text">
        <h3>What is LM UM?</h3>
        <p class="p-text">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugiat natus
          dolorem cumque iusto quidem velit? Obcaecati at quia nesciunt
          consectetur.
        </p>
        <p class="p-text">
          <b>Remember, </b>Lorem, ipsum dolor sit amet consectetur adipisicing
          elit. Repellat corporis asperiores vero quisquam tempore dolorum!
        </p>

        <p class="p-text">Life Mib Team</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Blogpost",
};
</script>

<style scoped>
.blog-wrapper {
  display: flex;
  flex-direction: column;
  background-color: #f9f9f9;
  margin-bottom: 30px;
  /* height: 80vh; */
}

.blog-content {
  display: flex;
  flex-direction: row;
  justify-content: center;
  height: 70vh;
}

.blog-left {
  max-width: 50%;
  padding: 72px 24px;
}

h2 {
  font-size: 45px;
  font-weight: 700;
  text-transform: uppercase;
  margin-bottom: 24px;
  color: rgb(41, 41, 165);
}

p {
  font-size: 15px;
  font-weight: 300;
  line-height: 1.7;
  margin-bottom: 30px;
  color: rgb(42, 42, 105);
}

.UW-links {
  display: inline-flex;
  flex-direction: row;
  align-items: center;
  border: 1px solid;
  border-radius: 25px;
  width: 190px;
  height: 120px;
  justify-content: center;
  margin: 50px 0 0 50px;
  text-decoration: none;
  text-transform: uppercase;
}

.UW-links:hover {
  border: 2px solid;
  border-color: teal;
}

.terms {
  text-decoration: none;
  font-size: 26px;
  font-weight: 900;
  color: rgb(182, 182, 21);
}

.swli {
  text-decoration: none;
  font-size: 26px;
  font-weight: 900;
  color: rgb(182, 182, 21);
}

.blog-right {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  order: 1;
  flex: 3;
}

img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
  
  .text {
    position: absolute;
    color: #fff;
    /* padding: 20px 200px 20px 20px; */
  }

h3 {
  text-align: left;
  color: #fff;
  margin-left: 50px;
}

.p-text {
  text-align: left;
  margin-left: 50px;
  color: #fff;
  width: 80%;
}

b {
  color: #fff;
}
</style>