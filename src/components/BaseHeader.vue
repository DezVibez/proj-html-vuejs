<template>
  <div>
    <ul class="d-flex">
      <li class="mx-3" v-for="(listItem, index) in list" :key="index">{{listItem}}</li>
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'BaseHeader',
  props: {
    list: Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../assets/sass/vars";

</style>
