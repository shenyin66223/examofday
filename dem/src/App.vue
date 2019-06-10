<template>
  <div id="app">
    <header>hello world</header>
    <router-view/>
    <footer>尾部</footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html,body{
  width: 100%;
  height: 100%;
}
#app {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
}
header,footer{
  height: 40px;
  line-height: 40px;
  font-size: 18px;
  text-align: center;
}
</style>
