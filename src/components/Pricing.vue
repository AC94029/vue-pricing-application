<template>
  <div class="container py-3">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Footer from './Footer.vue';
import Header from './Header.vue';
import Main from './Main.vue';

export default defineComponent({
  name: 'Pricing',
  components: {
    Footer,
    Header,
    Main
  }
});
</script>

<style scoped>

</style>