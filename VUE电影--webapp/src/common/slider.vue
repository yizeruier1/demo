<template>
  <yd-slider autoplay="3000">
    <yd-slider-item>
        <a href="http://www.ydcss.com">
            <img src="http://static.ydcss.com/uploads/ydui/1.jpg">
        </a>
    </yd-slider-item>
    <yd-slider-item>
        <a href="http://www.ydcss.com">
            <img src="http://static.ydcss.com/uploads/ydui/2.jpg">
        </a>
    </yd-slider-item>
    <yd-slider-item>
        <a href="http://www.ydcss.com">
            <img src="http://static.ydcss.com/uploads/ydui/3.jpg">
        </a>
    </yd-slider-item>
  </yd-slider>
</template>

<script type="text/javascript">
  import {Slider, SliderItem} from 'vue-ydui/dist/lib.rem/slider'
  export default {
    name: 'slider',
    components: {
      Slider,
      SliderItem
    },
    data() {
      return {
        
      }
    }
  }
</script>

<style scoped>

</style>