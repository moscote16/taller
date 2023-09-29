<template>
  <img alt="Vue-logo" src="./assets/inteligencia.jpg" class="im">
  <PostContainer/>
  <a href="https://www.wipo.int/wipo_magazine/es/2016/06/article_0002.html" target="_blank">Avances</a>
</template>

<script lang="ts">
import{defineComponent, DefineComponent} from 'vue';
import PostContainer from './components/PostContainer.vue';
export default defineComponent({
   components:{
     PostContainer
   }
 })

</script>

<style lang="scss">
  .im{
    width: 200px;
    height: 200px;
  }
  
</style>

