<template>
  <div>
    <span v-for="(item, index) in articles" :key="index">
      {{item}}
    </span>
  </div>
</template>

<script>
export default {
name: "my-article",
  props:['articles']
}
</script>

<style scoped>

</style>
