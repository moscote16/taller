<template>
    <div class="post-crad">
        <h3>{{ title }}</h3>
        <p> {{ summary}} </p>
        <p>{{ text }}</p>
        <post-button/>
        <post-delete/>
    </div>
</template>
   
<script lang="ts">
   import{defineComponent, DefineComponent} from 'vue';
  
    import PostButton from './PostButton.vue';
    import PostDelete from './PostDelete.vue';
        export default defineComponent({
            components:{
                PostButton,
                PostDelete
                
            },
            props:{
                title:{
                    type: String, 
                    default:""
                },
                summary:{
                    type: String, 
                    default:""
                },
                text:{
                    type: String, 
                    default:""
                }
                
            }
        })
</script>
   
<style lang="scss" scoped>
  
</style>