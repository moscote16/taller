<template>
    <div class="post-container">
        <PostCrad v-for="post in posts " :key="post.title"
        :title="post.title"
        :summary="post.summary"
        :text="post.text"
        />
        

    </div>
   </template>
   
   <script lang="ts">
    import{DefineComponent, defineComponent} from 'vue';
    import PostCrad from './PostCrad.vue';
    import datos from "@/assets/posts.json"
    export default defineComponent({
        name:"PostContainer",
        components:{
            PostCrad
        },
        computed:{
            posts: ()=>{
                return datos.map((post:any)=> {
                    return post
                })
            }
        }
    })
   </script>
   
   <style lang="scss" scoped>
    .post-container{
        border-radius: 15px;
        padding: flex;
        flex-wrap: wrap;
    }
   </style>
