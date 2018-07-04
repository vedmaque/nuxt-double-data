<template>
  <div>
    <h3>Parent / Child 2 Page</h3>
    <nuxt-link to="/parent/child1">Now go back to Child 1 Page</nuxt-link>
    <p>Or you could just press back button in browser</p>
  </div>
</template>

<script>
export default {
  data() {
    console.log('parent/child2.vue data')
    return {}
  },
  created() {
    console.log('parent/child2.vue created')
  },
  mounted() {
    console.log('parent/child2.vue mounted')
  }
}
</script>
