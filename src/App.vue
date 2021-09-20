<template>
  <div class="app bg-gradient-to-r from-gray-900 via-green-900 to-green-700">

    <div class="nav">
      <router-link to="/">Home</router-link>
    </div>

    <div class="body mt-16 mb-16">
      <router-view/>
    </div>

  </div>  
</template>
<style >

.body{
  display: grid;
  text-align: center;
  
}
</style>
 