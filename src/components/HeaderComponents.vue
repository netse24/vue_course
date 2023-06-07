<template>
  <nav>
    <div class="head-left">
      <div class="group-logo">
        <img src="../assets/logo.png" alt="" class="logo" />
        <h1 class="logo-name">Vue.NET</h1>
      </div>
      <ul>
        <li><a href="#">HOME</a></li>
        <li><a href="#">ABOUT</a></li>
        <li><a href="#">SERVICES</a></li>
        <li><a href="#">CONTACT</a></li>
      </ul>
    </div>
    <div class="head-right">
      <div class="btn-group">
        <a href="/post">
          <button class="login">LOGIN</button>
        </a>
        <button class="register">REGISTER</button>
      </div>
    </div>
  </nav>
</template>


<script >
export default {
  name: "HeaderComponents",
};
</script>

<style scoped>
template {
  padding: 0;
  margin: 0;
}

nav {
  background: #000;
  width: 100%;
  height: 10vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.head-left {
  padding: 10px;
  display: flex;
  align-items: center;
}
.group-logo {
  display: flex;
}
.logo {
  padding-right: 5%;
  width: 16%;
  height: 100%;
}
.logo-name {
  color: #fff;
}
ul {
  width: 100%;
  display: flex;
  justify-content: space-between;
  /* color: #4fc08d; */
}

ul > li > a {
  list-style: none;
  text-decoration: none;
  color: #ffffff;
}
button {
  padding: 10px;
  font-weight: bold;
  border: none;
  border-radius: 5px;
  margin: 2px;
}
</style>