<!--cesium模块布局-->
<template>
  <div class="app-wrapper">
    <!--导航栏-->
    <navbar/>
    <!--主页面-->
    <app-main/>
  </div>
</template>

<script lang="ts" setup>
// Components
import AppMain from "./component/appMain.vue"
import Navbar from "./component/navbar.vue"
</script>

<style lang="scss" scoped>
.app-wrapper {
  position: fixed;
  top: 0;
  height: 100%;
  width: 100%;
  overflow: hidden;
  pointer-events: none;
}
</style>
