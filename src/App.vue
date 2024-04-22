<script>
import { store } from './store.js';
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppCoaching from './components/AppCoaching.vue';


export default {
  components: {
    AppHeader,
    AppHero,
    AppCoaching,

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
  <AppHero></AppHero>
  <AppCoaching></AppCoaching>
</template>

<style lang="scss">
  @use './style/generic';
</style>


