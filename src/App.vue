<script>
import axios from 'axios';
import {store} from './store';
import HeaderVue from './components/HeaderVue.vue';
import MainVue from './components/MainVue.vue';
import FooterVue from './components/FooterVue.vue';

export default{
  name: "App",
  components: {
    HeaderVue,
    MainVue,
    FooterVue
  },
  data(){
    return{
      store
    }
  },
  created(){
    
    
    
  },
  computed:{
    

  },
  methods: {
   
    
  
}
}

</script>

<template>
  <div>
    <HeaderVue/>
    <MainVue/>
    <FooterVue/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;


</style>
