<template>
  <div>
    <h3>Parent / Child 1 Page</h3>
    <nuxt-link to="/parent/child2">Go to Child 2 Page</nuxt-link>
  </div>
</template>

<script>
export default {
  data() {
    console.log('parent/child1.vue data')
    return {}
  },
  created() {
    console.log('parent/child1.vue created')
  },
  mounted() {
    console.log('parent/child1.vue mounted')
  }
}
</script>
