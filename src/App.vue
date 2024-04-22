<script>
import { store } from './store.js';
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';


export default {
  components: {
    AppHeader,
    AppHero,

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
</template>

<style lang="scss">
  @use './style/generic';
</style>


