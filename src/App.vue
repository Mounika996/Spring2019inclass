<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>
<script>
import Nav from '@/components/Nav;'
export default {
    components:{}
    Nav
  }
}
</script>


<style lang="scss">

</style>