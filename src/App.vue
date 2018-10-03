<template>
  <div id="app">
    <header>  
      <div>
        <b-navbar toggleable="md" type="dark" variant="dark">
          <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
          <b-navbar-brand href="#">JC</b-navbar-brand>
          <b-collapse is-nav id="nav_collapse">
            <b-navbar-nav>
              <b-nav-item href="#">About</b-nav-item>
              <b-nav-item href="#">Experiences</b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </header>
    <myWork/>

    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <myWork msg="Welcome to Your Vue.js App"/> -->

  </div>
</template>

<script>
import myWork from "./components/myWork.vue";
export default {
  name: "app",
  components: {
    myWork
  }
};

</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
