<template>

  <div class="hello">
    <b-jumbotron header="Bootstrap Vue" lead="Bootstrap 4 Components for Vue.js 2" >
      <transition name="alert-in" enter-active-class="animated flipInX" leave-active-class="animated flipOutX">
        <p>For more information visit website</p>
      </transition>
      <b-btn variant="primary" href="#">More Info</b-btn>
    </b-jumbotron>
  </div>
</template>

<script>

export default {
  name: 'myWork',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}

</style>
