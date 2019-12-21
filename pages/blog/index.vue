<template>
<div>
   <h1>{{blogPost.title}}</h1>
    <div>{{blogPost.body}}</div>
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
