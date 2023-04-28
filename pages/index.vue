<template>
  <main>
    <!-- <TheNavBar /> -->
    <h1>Home page</h1>
    <nuxt-link
      v-for="post in posts"
      :key="post.id"
      :to="{ name: 'posts-id', params: { id: post.id } }"
      >{{ post.title }}</nuxt-link
    >
  </main>
</template>

<script>
export default{
  computed: {
    posts () {
      return this.$store.state.all
    }
  },
}
</script>

<script scoped>
// import TheNavBar from '~/components/TheNavBar.vue'
// export default {
//   components: TheNavBar,
// }
</script>
