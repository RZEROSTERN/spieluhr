<template>
  <div id="app" class="font-sans static">
    <div class="grid grid-cols-8 gap-0">
      <div class="col-span-1">
        <Sidebar />
      </div>
      <div class="col-span-7">
        <router-view/>
      </div>
    </div>
    <div class="absolute inset-x-0 bottom-0 grid grid-cols-1">
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
