<template>
  <div>
    <Banner />
    <h1>게시물 목록</h1>
    <PostList />
  </div>
</template>

<script>
import Banner from '../components/common/Banner.vue'
import PostList from '../components/posts/PostList.vue'

export default {
  components: { Banner, PostList }
}
</script>
