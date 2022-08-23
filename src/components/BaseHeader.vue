<template>
  <div class="hello">
    <h1 v-for="(listItem, index) in list" :key="index">{{listItem}}</h1>
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

</style>
