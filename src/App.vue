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
import AppEvents from './components/AppEvents.vue';
import AppNewsletter from './components/AppNewsletter.vue';
import AppFooter from './components/AppFooter.vue';

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
    AppEvents,
    AppNewsletter,
    AppFooter

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
      ],

      

      informationLinks: [
          {
          title: 'Membership'
         },

         {
          title: 'Purchase Guide'
         },

         {
          title: 'Privacy policy'
         },

         {
          title: 'Term of service'
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
  <AppHeader :navLinks="headerNavLinks"></AppHeader>
  <main>
    <AppHero></AppHero>
    <AppCoaching></AppCoaching>
    <AppMentor></AppMentor>
    <AppYoutube></AppYoutube>
    <AppTestimonials></AppTestimonials>
    <AppCourses></AppCourses>
    <AppBlog></AppBlog>
    <AppEvents></AppEvents>
    <AppNewsletter></AppNewsletter>
  </main>
  <AppFooter :positionNav="positionLinks" :explore="exploreLinks" :info="informationLinks"></AppFooter>   
</template>

<style lang="scss">
  @use './style/generic';
</style>


