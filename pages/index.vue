<template>
  <div>
    <h3>This is repo created to show the unfamous nuxt double data bug</h3>
    <nuxt-link to="/parent/child1">Go to Parent / Child 1 Page</nuxt-link>
  </div>
</template>

<script>
export default {
  data() {
    console.log('index.vue data')
    return {}
  },
  created() {
    console.log('index.vue created')
  },
  mounted() {
    console.log('index.vue mounted')
  }
}
</script>

