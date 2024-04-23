<script>
import { store } from './store.js';
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppCoaching from './components/AppCoaching.vue';
import AppMentor from './components/AppMentor.vue';
import AppYoutube from './components/AppYoutube.vue';
import AppTestimonials from './components/AppTestimonials.vue';
import AppCourses from './components/AppCourses.vue';
import AppBlog from './components/AppBlog.vue';

export default {
  components: {
    AppHeader,
    AppHero,
    AppCoaching,
    AppMentor,
    AppYoutube,
    AppTestimonials,
    AppCourses,
    AppBlog,

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
    <AppYoutube></AppYoutube>
    <AppTestimonials></AppTestimonials>
    <AppCourses></AppCourses>
    <AppBlog></AppBlog>
  </main>   
</template>

<style lang="scss">
  @use './style/generic';
</style>


