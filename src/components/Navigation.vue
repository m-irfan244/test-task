<template>
  <header>
    <nav class="navbar">
      <div class="branding">
        <router-link class="header" to="#"> Life Mib</router-link>
      </div>
      <div class="nav-links">
        <ul>
          <router-link class="link" to="#">LM UW</router-link>
          <router-link class="link" to="#">Learning</router-link>
          <router-link class="link" to="#">Smartlife</router-link>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Navigation",
};
</script>

<style scoped>
header {
  background-color: #fff;
  padding: 0 20px;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1),
    0 2px 4px -1px rgba(0, 0, 0, 0.06);
  z-index: 99;
}

.navbar {
  max-width: 1440px;
  margin: 0 auto;
  height: 15px;
}

.link {
  font-weight: 500;
  padding: 0 3px;
  transition: 0.3s color ease;
}

.link:hover {
    color: #1eb8e8;
}

nav {
  display: flex;
  padding: 25px 0;
}

.branding {
  display: flex;
  align-items: center;
}

.header {
  font-weight: 600;
  font-size: 24px;
  color: #000;
  text-decoration: none;
}

.nav-links {
  position: relative;
  display: flex;
  flex: 1;
  align-items: center;
  justify-content: flex-end;
  
}

ul {
  margin-right: 32px;
}

.link {
  margin-right: 32px;
  color: #000;
  text-decoration: none;
}

.link:last-child {
  margin-right: 0;
}
</style>>