<template>
  <Header/>
  <router-view/>
  <Footer/>
</template>
<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',

  components: {
    Header,
    Footer
  }
}
</script>
<style>
* {
  width: 100%;
  margin: 0;
  padding: 0;
}
</style>
