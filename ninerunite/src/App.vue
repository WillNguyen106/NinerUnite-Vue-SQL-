<template>
  
  <!-- <nav>
      <router-link to="/">NinerUnite</router-link> |
      <router-link to="/signUp">Sign Up</router-link> |
      <router-link to="/logIn">Login</router-link>
    </nav> -->
    <Header />
  <!-- <router-view/> -->
</template>

<script>
import Header from '@/components/Header.vue'
export default {
  components:{
    Header
  }
  //this is a test
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
