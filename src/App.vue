<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <a href="https://www.electronjs.org/" target="_blank">
      <img src="/electron.svg" class="logo electron" alt="Electron logo" />
    </a>
    <a href="https://www.typescriptlang.org/" target="_blank">
      <img src="./assets/typescript.svg" class="logo typescript" alt="Typescript logo" />
    </a>
    <a href="https://sass-lang.com/" target="_blank">
      <img src="./assets/sass.svg" class="logo sass" alt="Sass logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue + Electron + Ts + Sass" />
</template>

<style scoped lang="scss">
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);

  &.vue {
    filter: drop-shadow(0 0 2em #42b883aa);
  }

  &.electron {
    filter: drop-shadow(0 0 2em #0e22dbaa);
  }

  &.typescript {
    filter: drop-shadow(0 0 2em #5571f0);
  }

  &.sass {
    filter: drop-shadow(0 0 2em #ee389c);
  }
}

</style>
