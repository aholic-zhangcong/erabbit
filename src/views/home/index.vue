<template>
  <div class="page-home">
    <div class="home-entry">
      <div class="container">
        <!-- 左侧分类 -->
        <HomeCategory/>
        <HomeBanner/>
      </div>
    </div>
    <!--新鲜好物-->
    <HomeNew/>
    <!--人气推荐-->
    <HomeHot/>
    <!--热门品牌-->
    <HomeBrand/>
    <!-- 商品区域 -->
    <HomeProduct/>
  </div>
</template>
<script>
import HomeCategory from './components/home-category'
import HomeBanner from './components/home-banner'
import HomeNew from './components/home-new'
import HomeHot from './components/home-hot'
import HomeBrand from './components/home-brand'
import HomeProduct from './components/home-product'

export default {
  name: 'PageHome',
  components: {
    HomeCategory,
    HomeBanner,
    HomeNew,
    HomeHot,
    HomeBrand,
    HomeProduct
  }
}
</script>
<style scoped lang="less">

</style>
