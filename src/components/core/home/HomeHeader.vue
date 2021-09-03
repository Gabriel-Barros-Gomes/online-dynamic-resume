<template>
  <div class="home-header">
    <div class="grid gap-4 grid-cols-5">
     
     <div></div>
     <div></div>
     <div><img
        class="effect "
        src="../../../assets/profile.png"
        alt="profile-photo.png"
      /></div>
     <div></div>
     <div></div>
      
      
    </div>

    <div class="title">
      <label> Gabriel Barros Gomes </label>
    </div>

    <div class="contacts">
      <div class="subtitle">Contatos</div>
      <div>
        <label class="email">gabrielgomes12394@gmail.com</label>
        <label class="phone">(61) 9 8146-0577</label>
        <div class="linkedin">
         <a
            href="https://www.linkedin.com/in/gabriel-barros-gomes-642761156/"
            title="https://www.linkedin.com/in/gabriel-barros-gomes-642761156/"
            class=""
            >
            <div>
              <img
                width="32"
                height="32"
                src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTkgMGgtMTRjLTIuNzYxIDAtNSAyLjIzOS01IDV2MTRjMCAyLjc2MSAyLjIzOSA1IDUgNWgxNGMyLjc2MiAwIDUtMi4yMzkgNS01di0xNGMwLTIuNzYxLTIuMjM4LTUtNS01em0tMTEgMTloLTN2LTExaDN2MTF6bS0xLjUtMTIuMjY4Yy0uOTY2IDAtMS43NS0uNzktMS43NS0xLjc2NHMuNzg0LTEuNzY0IDEuNzUtMS43NjQgMS43NS43OSAxLjc1IDEuNzY0LS43ODMgMS43NjQtMS43NSAxLjc2NHptMTMuNSAxMi4yNjhoLTN2LTUuNjA0YzAtMy4zNjgtNC0zLjExMy00IDB2NS42MDRoLTN2LTExaDN2MS43NjVjMS4zOTYtMi41ODYgNy0yLjc3NyA3IDIuNDc2djYuNzU5eiIvPjwvc3ZnPg=="
              />
              <div>Linkedin</div>
            </div>
            </a
          >


        </div>
        <div class="github">
          <a
            href="https://github.com/Gabriel-Barros-Gomes"
            title="https://github.com/Gabriel-Barros-Gomes"
          >
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="32"
                height="32"
                viewBox="0 0 24 24"
              >
                <path
                  d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
                />
              </svg>
              <div>Github</div>
            </div>
          </a>
        </div>
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
  setup() {
    const showContacts = ref<boolean>(false);

    return {
      showContacts,
    };
  },
});
</script>

<style scoped>
.home-header {
  padding: 2rem;
}
.title {
  font-size: 1.7rem;
  padding-bottom: 1rem;
}
.subtitle {
  font-size: 1.4rem;
  padding-bottom: 1rem;
}
.email,
.phone,
.linkedin,
.github,
.address,
.job {
  padding: 0.5rem;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
}
.effect {
  border-radius: 50%;
  background-position: -15px -15px;
  height: 20rem;
  width: 20rem;
  padding: 3rem;
  position: relative;
  box-sizing: border-box;
  cursor: pointer;
  transition: all 400ms ease;
  
}
</style>
