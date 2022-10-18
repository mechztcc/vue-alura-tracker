<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <SideNav />
    </div>
    <div class="column isthree-quarter">
      <Form />
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import SideNav from './components/SideNav.vue';
import Form from './components/Form.vue';


export default defineComponent({
  name: "App",
  components: { SideNav, Form }
});
</script>

<style>

</style>
