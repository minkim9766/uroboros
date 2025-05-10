<template>
  <div>
    <Banner />
    <div class="main-stage">
      <div class="upper-stage">
        <SNS />
        <Help />
      </div>
      <div class="bottom-stage">
        <ProductList />
      </div>
    </div>
  </div>
</template>

<script>
import Banner from '../components/common/Banner.vue'
import SNS from '../components/home/SNS.vue'
import Help from '../components/home/Help.vue'
import ProductList from '../components/home/ProductList.vue'

export default {
  components: { Banner, SNS, Help, ProductList }
}
</script>
