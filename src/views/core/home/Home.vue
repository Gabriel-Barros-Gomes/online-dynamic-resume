<template>
  <div class="home">
    
    <div id="header">
      <HomeHeader/>
    </div>

    <div id="canvas">
      <HomeCanvas/>
    </div>

    <div id="footer">
      <HomeFooter/>
    </div>
    
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HomeHeader from '../../../components/core/home/HomeHeader.vue';
import HomeCanvas from '../../../components/core/home/HomeCanvas.vue';
import HomeFooter from '../../../components/core/home/HomeFooter.vue';

export default defineComponent({
  name: 'Home',
  components: {
    HomeHeader,
    HomeCanvas,
    HomeFooter
  },
});
</script>
