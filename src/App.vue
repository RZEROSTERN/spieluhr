<template>
  <div id="app" class="font-sans">
    <div class="grid grid-cols-8 gap-0">
      <div class="col-span-1">
        <Sidebar />
      </div>
      <div class="col-span-7">
        <router-view/>
      </div>
    </div>
    <div class="grid grid-cols-1">
      <Player />
    </div>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue';
import Player from './components/Player.vue';

export default {
  components: {Sidebar, Player}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

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
