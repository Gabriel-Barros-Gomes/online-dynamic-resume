<template>
  <div class="home-canvas">
    <div class="content">
      <label id="title">Tecnologias</label>
      <label @mouseenter=" contentWeb = true"  >
        Desenvolvimento web
      </label>
      <div v-show="contentWeb" @mouseleave=" contentWeb = false">
        <div>Java</div>
        <div>Javascript</div>
        <div>Ruby on Rails</div>
      </div>

      <label @mouseenter=" contentDesktop = true">
        Desenvolvimento desktop
      </label>
      <div @mouseleave=" contentDesktop = false" v-show="contentDesktop">
        <div>Java</div>
        <div>C,C++,C#</div>
        <div>Ruby</div>
        <div>Python</div>
      </div>

      <label @mouseenter=" contentOthers = true">
        Outros
      </label>
      <div @mouseleave=" contentOthers = false" v-show="contentOthers">
        <div>DDD</div>
        <div>Microservices</div>
        <div>Docker</div>
        <div>Build</div>
        <div>Versionamento</div>
        <div>Deploy</div>
        <div>Documentação</div>
      </div>

      <label @mouseenter=" contentProfessional = true">Experiências profissionais</label>
      <div @mouseleave=" contentProfessional = false" v-show="contentProfessional">
        <div>ISGH - IsSaude</div>
        <div>MEI</div>
        <div>Fortaleza Serviços</div>
        
      </div>

      <label @mouseenter=" contentEducational = true">Educação</label>
      <div @mouseleave=" contentEducational = false" v-show="contentEducational">
        <div>UnB - Universidade de Brasília</div>
        <div>Trybe</div>
        <div>Técnico em informática</div>
        <div>Cursos de programação</div>
        
      </div>

      <label @mouseenter=" contentProjects = true">Projetos</label>
      <div @mouseleave=" contentProjects = false" v-show="contentProjects">
        <div>GBG Gerência</div>
        
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
#title{
  font-size: 1.7rem;
  padding-bottom: 1rem;
}
p, ul {
  padding: 1.5rem;
  transition: width 2s;
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
    const contentWeb = ref<boolean>(false)
    const contentDesktop = ref<boolean>(false)
    const contentOthers = ref<boolean>(false)
    const contentProfessional = ref<boolean>(false)
    const contentEducational = ref<boolean>(false)
    const contentProjects = ref<boolean>(false)

    return{
      contentWeb,
      contentDesktop,
      contentOthers,
      contentProfessional,
      contentEducational,
      contentProjects
    }
  }
});
</script>
