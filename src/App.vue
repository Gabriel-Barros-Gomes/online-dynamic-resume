<template>
  <div id="app">

    <div id="nav">
      <router-link to="/">Home</router-link>
    </div>

    <div id="body">
      <router-view/>
    </div>

  </div>  
</template>
<style >
#body{
  display: grid;
  text-align: center;
  margin-top: 5rem;
  margin-bottom: 5rem;
  font-family: Verdana, Arial, Helvetica, sans-serif;
}
</style>
