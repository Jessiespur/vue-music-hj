<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view class="container"></router-view>
    </keep-alive>
  </div>
</template>

<script>
  import MHeader from 'components/m-header/m-header'
  import Tab from 'components/tab/tab'
  export default {
    name: 'app',
    components: {
      MHeader, Tab
    }
  }
</script>

<style>
  .conatainer{
    padding: 20px 20px;
    color: #fff;
  }
</style>
