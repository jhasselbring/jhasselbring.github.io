<template>
  <a :href="href">
    <span class="uppercase px-4 py-2 bg-green-500 m-4 rounded-md text-white">{{text}}</span>
  </a>
</template>

<script>
export default {
  props: ['text', 'href'],
}
</script>

<style scoped>

</style>
