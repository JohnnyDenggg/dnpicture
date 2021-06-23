<template>
  <view>
    <home-album></home-album>
    <home-category></home-category>
    <home-new></home-new>
    <home-recommend></home-recommend>
  </view>
</template>

<script>
import HomeAlbum from './homeAlbum/index'
import HomeNew from './homeNew/index'
import HomeRecommend from './homeRecommend/index'
import HomeCategory from './homeCategory/index'
export default {
  components: {
    HomeAlbum,
    HomeCategory,
    HomeNew,
    HomeRecommend
  }
}
</script>

<style>
</style>