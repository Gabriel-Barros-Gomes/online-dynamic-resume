<template>
  <div class="home p-5">
    <div class="card rounded-md z-40 shadow-md bg-white">
      <div class="content">
        <div class="home-header">
          <HomeHeader />
        </div>

        <div class="home-canvas">
          <HomeCanvas />
        </div>
      </div>
    </div>
    <div class="home-footer">
      <HomeFooter />
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


