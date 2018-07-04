<template>
  <nuxt-child />
</template>

<script>
export default {
  data() {
    console.log('parent.vue data')
    return {}
  },
  created() {
    console.log('parent.vue created')
  },
  mounted() {
    console.log('parent.vue mounted')
  }
}
</script>
