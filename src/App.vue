<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <SideNav />
    </div>
    <div class="column isthree-quarter"></div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import SideNav from './components/SideNav.vue';


export default defineComponent({
  name: "App",
  components: { SideNav }
});
</script>

<style>

</style>
