<template>
  <div>
    <div class="contentBox" v-cloak>
        <div class="home">
            <h1>{{ msg }}</h1>
            <h2>Essential Links</h2>
        </div>
    </div>
  </div>
</template>

<script type="es6">
export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
