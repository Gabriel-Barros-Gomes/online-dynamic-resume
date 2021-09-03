<template>
  <div class="home-canvas">
    <div class="content">
      <label class="title">Tecnologias</label>
      <label class="subtitle label">
        Desenvolvimento web
      </label>
      <div class="">
        <label>Java</label>
        <label>Javascript</label>
        <label>Ruby on Rails</label>
      </div>

      <label class="subtitle label">
        Desenvolvimento desktop
      </label>
      <div class="">
        <label>Java</label>
        <label>C,C++,C#</label>
        <label>Ruby</label>
        <label>Python</label>
      </div>

      <label class="subtitle label">
        Outros
      </label>
      <div class="" >
        <label>DDD</label>
        <label>Microservices</label>
        <label>Docker</label>
        <label>Build</label>
        <label>Versionamento</label>
        <label>Deploy</label>
        <label>Documentação</label>
      </div>

      <label class="subtitle label">Experiências profissionais</label>
      <div class="">
        <label>ISGH - IsSaude</label>
        <label>MEI</label>
        <label>Fortaleza Serviços</label>
        
      </div>

      <label class="subtitle label" >Educação</label>
      <div class="">
        <label>UnB - Universidade de Brasília</label>
        <label>Técnico em informática</label>
        <label>Cursos de programação</label>
        
      </div>

      <label class="subtitle label">Projetos</label>
      <div class="" >
        <label>GBG Gerência</label>
        
      </div>


    </div>

  </div>
</template>

<style scoped>
.home-canvas{
  padding: 5rem;
}
.content{
  font-size: 1.2rem;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
   
}
.title{
  padding-top: 1rem;
  padding-bottom: 1rem;
}
.subtitle{
  padding-top: 5rem;
  padding-bottom: 1rem;
  font: bold, italic;
  font-size: 1.5rem;
}

p, ul {
  padding: 1.5rem;
  
}
label {
 font-style: italic;
 padding: 1rem;
}
</style>


<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'HomeCanvas',
  components: {
  
  },
  setup(){
    
    return{
     
    }
  }
});
</script>
