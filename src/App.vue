<template>
  <div id="app">
    <div id="nav">
        <Header></Header>
        <!-- <router-link to="/">Home</router-link>
        <router-link to="/contactUs">About</router-link> -->
        <router-view/>
    </div>
    
  </div>
</template>
<script>
import Header from '@/views/header/header.vue'
export default {
    components: {
        Header
    }
}
</script>
<style lang="less">
a {
    text-decoration: none;
    out-line: none;
    color: #fff;
}
</style>
