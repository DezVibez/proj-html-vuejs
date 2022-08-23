<template>
  <div id="app">
    <BaseHeader :list="avadaList"/>
    <BaseMain />
    <BaseFooter :list="avadaList"/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import BaseFooter from './components/BaseFooter.vue';

//"Who We Are","What We Do","Where We Work","Careers","News","Get In Touch Now"

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    BaseFooter
  },
  data() {
    return {
      avadaList:["Home","Who We Are","Where We Work","Careers","News","Get In Touch Now"] 
    }
  },
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
