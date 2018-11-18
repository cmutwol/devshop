<template>
  <div id="app">
    <Header/>
    <div class="container">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
     <router-view />
     
    </div>
  </div>
</template>

<script>
import Header from "./shared/headers/Header.vue";
  export default {
     data() {
       return {
         
       }
     },
     components: {
      Header
     }
  }
</script>
<style lang="scss">

#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
