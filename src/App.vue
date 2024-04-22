<script>
import { store } from './store.js';
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppCoaching from './components/AppCoaching.vue';
import AppMentor from './components/AppMentor.vue';

export default {
  components: {
    AppHeader,
    AppHero,
    AppCoaching,
    AppMentor,

  },

  data() {
    return {
      store,
      headerNavLinks: [
         {
          title: 'Home'
         },

         {
          title: 'Pages'
         },

         {
          title: 'Courses'
         },

         {
          title: 'Features'
         },

         {
          title: 'Blog'
         },

         {
          title: 'Shop'
         },
      ]
    };
  },
  
  methods: {
   
  },
  mounted() {
   
  }
}
</script>

<template>
  <AppHeader :navLinks="headerNavLinks" ></AppHeader>
  <main>
    <AppHero></AppHero>
    <AppCoaching></AppCoaching>
    <AppMentor></AppMentor>
  </main>   
</template>

<style lang="scss">
  @use './style/generic';
</style>


