<template>
  <div class="home-header">
    <div>
      <img src="../../../assets/profile.png" alt="profile-photo.png">
    </div>

    <div class="title">
      <label> Gabriel Barros Gomes </label>
    </div>

    <div class="contacts">
      <div class="subtitle" @mouseenter="showContacts = true"> Contatos </div>
      <div v-show="showContacts" @mouseleave="showContacts = false">
          <label class="email">gabrielgomes12394@gmail.com</label>
          <label class="phone">(61) 9 8146-0577</label>
          <div class="linkedin"><a href="https://www.linkedin.com/in/gabriel-barros-gomes-642761156/" title="https://www.linkedin.com/in/gabriel-barros-gomes-642761156/">Linkedin</a></div>
          <div class="github"><a href="https://github.com/Gabriel-Barros-Gomes" title="https://github.com/Gabriel-Barros-Gomes">Github</a></div>
          <label class="address">Brasília/DF</label>
          <label class="job">Desenvolvedor Fullstack</label>
      </div>
    </div>

  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "HomeHeader",
  setup(){

    const showContacts = ref<boolean>(false)

    return{
      showContacts
    }
  }
 
});
</script>

<style scoped>
.home-header{
  padding: 2rem;
  
}
.title{
  font-size: 1.7rem;
  padding-bottom: 1rem;
}
.subtitle{
  font-size: 1.4rem;
  padding-bottom: 1rem;
}
.email, .phone, .linkedin, .github, .address, .job{
  padding: 0.5rem;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
}
img{
  border-radius: 50%;
  background-position: -15px -15px;
  height: 195px;
  width: 195px;
  padding: 3rem;
}

</style>
