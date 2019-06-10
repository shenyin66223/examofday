<template>
  <main class="hello">
    简易首页
  </main>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  main{
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 20px;
    color: blue;
    border-top: 1px solid #555;
    border-bottom: 1px solid #555;
  }
</style>
