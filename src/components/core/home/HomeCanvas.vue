<template>
  <div class="home-canvas">
     <main
      className=" flex flex-col items-center justify-center w-full flex-1 px-20 text-center"
    >
    <div class="content mb-6">
      <label class="title text-4xl font-bold">Tecnologias</label>

      <div class=" group">
      <label class="subtitle text-3xl block mt-1 mb-3 text-green-700 ">
        Desenvolvimento web
      </label>
      <div class="text-web">
        <label class="text-2xl block mt-1 mb-3">Java</label>
        <label class="text-2xl block mt-1 mb-3">Javascript</label>
        <label class="text-2xl block mt-1 mb-3">Ruby on Rails</label>
      </div>
      </div>

      <label class="subtitle text-3xl block mt-1 mb-3 text-green-700">
        Desenvolvimento desktop
      </label>
      <div class=" text-desk">
        <label class="text-2xl block mt-1 mb-3">Java</label>
        <label class="text-2xl block mt-1 mb-3">C, C++, C#</label>
        <label class="text-2xl block mt-1 mb-3">Ruby</label>
        <label class="text-2xl block mt-1 mb-3">Python</label>
      </div>

      <label class="subtitle text-3xl block mt-1 mb-3 text-green-700 ">
        Outros
      </label>
      <div class="text-other" >
        <label class="text-2xl block mt-1 mb-3">DDD</label>
        <label class="text-2xl block mt-1 mb-3">Microservices</label>
        <label class="text-2xl block mt-1 mb-3">Docker</label>
        <label class="text-2xl block mt-1 mb-3">Build</label>
        <label class="text-2xl block mt-1 mb-3">Versionamento</label>
        <label class="text-2xl block mt-1 mb-3">Deploy</label>
        <label class="text-2xl block mt-1 mb-3">Documentação</label>
      </div>

      <label class="subtitle text-3xl block mt-1 mb-3 text-green-700">Experiências profissionais</label>
      <div class="text-experience">
        <label class="text-2xl block mt-1 mb-3">ISGH - IsSaude</label>
        <label class="text-2xl block mt-1 mb-3">MEI</label>
        <label class="text-2xl block mt-1 mb-3">Fortaleza Serviços</label>
        
      </div>

      <label class="subtitle text-3xl block mt-1 mb-3 text-green-700" >Educação</label>
      <div class="text-education">
        <label class="text-2xl block mt-1 mb-3" >Técnico em informática</label>
        <label class="text-2xl block mt-1 mb-3">Cursos de programação</label>
        
      </div>

      <label class="subtitle text-3xl block mt-1 mb-3 text-green-700">Projetos</label>
      <div class="text-projects" >
        <label class="text-2xl block mt-1 mb-3">GBG Gerência</label>
        
      </div>


    </div>
     </main>
  </div>
</template>


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
