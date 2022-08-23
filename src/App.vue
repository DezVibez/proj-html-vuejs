<template>
  <div>
    <BaseHeader :list="avadaList"/>
    <BaseMain />
    <BaseFooter :list="avadaList"/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import BaseFooter from './components/BaseFooter.vue';

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
  @import "./assets/sass/style.scss";
</style>
