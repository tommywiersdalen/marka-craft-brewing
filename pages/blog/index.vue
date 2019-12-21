<template>
<div>
  <p>test</p>
</div>
</template>

<script>
export default {
computed: {
    blogPosts() {
      return this.$store.state.blogPosts;
    },
  },
}
</script>

<style>

</style>
