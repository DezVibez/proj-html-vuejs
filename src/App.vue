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
  *{
    list-style-type: none;
    padding: 0;
    margin: 0; 
    box-sizing: border-box;
  }
}
</style>
