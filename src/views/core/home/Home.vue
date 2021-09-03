<template>
  <div class="home">
    <div class="card">
      <div class="content">
        <div class="home-header">
          <HomeHeader />
        </div>

        <div class="home-canvas">
          <HomeCanvas />
        </div>

        <div class="home-footer">
          <HomeFooter />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HomeHeader from "../../../components/core/home/HomeHeader.vue";
import HomeCanvas from "../../../components/core/home/HomeCanvas.vue";
import HomeFooter from "../../../components/core/home/HomeFooter.vue";

export default defineComponent({
  name: "Home",
  components: {
    HomeHeader,
    HomeCanvas,
    HomeFooter,
  },
});
</script>

<style scoped>
.home{
  padding-right: 5rem;
  padding-left: 5rem;
  
}
.card{
  background-color: rgb(255, 255, 255);
}
</style>
