<script>
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';

  export default{
    data(){
      return{
        
      }
    },
    components: {
      AppTitle,
      AppHero
    }
  }

  console.log(AppTitle)
</script>

<template>
  <AppTitle/>
  <AppHero/>
</template>