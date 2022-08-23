<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">

    <MyTitle />
    <Jumbo_Hero/>

  </div>
</template>

<script>

import MyTitle from "@/components/MyTitle.vue";
import Jumbo_Hero from "@/components/Jumbo_Hero.vue";
    
export default {
  name: "app",
  components: {
    MyTitle,
    Jumbo_Hero
}
}

</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
