<template>

    <div class="container">
      <div id="nav">
      <img width="120px" src="../assets/logo-chilltrip.png" alt="logo" class="float-left">
      <router-link to="/">Home</router-link>
      <router-link to="/apps">Apps</router-link>
      <router-link to="/blog">Blog</router-link> 
      <router-link to="/about-us">About Us</router-link>
      <router-link to="/contact">Contact</router-link>
      <router-link to="/sign-up"><button class="btn btn-primary px-5 py-2 ml-4 btn-sign-up">Get Started</button></router-link>
    </div>
    <router-view/>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
export default {
name : "Navigation"
}

</script>

<style scoped>
#nav {
  padding: 30px;
  text-align: right;
  margin-top: 0px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin-right: 20px;
}

#nav a.router-link-exact-active {
  color: #F8B70C;
}

.btn-sign-up {
    background: #F8B70C;
    border: 1px solid #F8B70C;
    border-radius: 7px;
    color: black;
    font-weight: bold; 
}

.btn-sign-up:hover {
    color: white;
}
</style>