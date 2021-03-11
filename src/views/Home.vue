<template>
  <div class="Home bg-gray-200" style="height: 2000px">
    <Header></Header>

    <main>
      <Banner></Banner>
      <Category></Category>
      <Search></Search>
      <PostNew></PostNew>
      <Content></Content>
      <Common></Common>
    </main>

    <Footer></Footer>
  </div>
</template>

<script>
export default {
  components: {
    Header: () => import("@/views/Header.vue"),
    Banner: () => import("@/views/Banner.vue"),
    Category: () => import("@/views/Category.vue"),
    Search: () => import("@/views/Search.vue"),
    PostNew: () => import("@/views/PostNew.vue"),
    Content: () => import("@/views/Content.vue"),
    Common: () => import("@/views/Common.vue"),
    Footer: () => import("@/views/Footer.vue"),
  },
};
</script>

<style lang="scss" scoped>

</style>