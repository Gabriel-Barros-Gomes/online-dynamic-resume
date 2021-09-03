<template>
  <div class="app">

    <div class="nav">
      <router-link to="/">Home</router-link>
    </div>

    <div class="body">
      <router-view/>
    </div>

  </div>  
</template>
<style >
.app{
  background-color: rgb(230, 230, 230);
}
.body{
  display: grid;
  text-align: center;
  margin-top: 5rem;
  margin-bottom: 5rem;
}
</style>
 