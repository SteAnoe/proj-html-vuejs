<script>
import SingleCard from './SingleCard.vue'
import {store} from '../store';

export default{
  name: "MainVue",
  components:{
    SingleCard
  },
  data(){
    return{
      store
    }
},
}
</script>

<template>

</template>

<style lang="scss" scoped>

</style>
