<template>
  <div class="sns">
    <div class="logo">
      <img class="logo-image" src="/images/logo.png" alt="도마뱀 카페 로고">
    </div>
    <h1 class="SNS-Text">SNS</h1>
    <div class="SNS-Icon">
      <a href="https://www.youtube.com" class="youtube-link">
        <img src="https://cdn-icons-png.freepik.com/256/1384/1384060.png?semt=ais_hybrid" class="youtube" alt="Youtube">
      </a>
      <a href="https://www.instagram.com" class="instagram-link">
        <img src="https://mblogthumb-phinf.pstatic.net/MjAyMTA5MTlfMjUg/MDAxNjMyMDE3OTA4NTA0...png" class="instagram" alt="Instagram">
      </a>
      <a href="https://www.twitter.com" class="twitter-link">
        <img src="https://cdn-icons-png.flaticon.com/512/3938/3938028.png" class="twitter" alt="twitter">
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SNS'
}
</script>

<style scoped>
.logo-image {
  width: 100px;
  height: auto;
  margin-bottom: 10px;
}
</style>
