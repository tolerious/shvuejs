<template>
  <div id="app">
    <menu-bar></menu-bar>
    <router-view />
  </div>
</template>

<style lang="less">
#app {
  background-color: #2a2a3a;
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  position: relative;
}
</style>
<script>
import menuBar from "@/components/menuBar.vue";
export default {
  components: {
    menuBar
  }
};
</script>