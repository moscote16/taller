<template>
    <button class="post-button">ver</button>
   </template>
   
   <script lang="ts">
        import{defineComponent, DefineComponent} from 'vue';
        export default defineComponent({
            name:"PostButton"
        })
   </script>
   
   <style lang="scss" scoped>
        .post-button{
            background-color: rgb(60, 255, 0);
            padding: 3px;
            border: solid 1px blue;
            &:hover{
                background-color: blue;
                border: solid px rgb(255, 0, 0);
                color: red;
            }
        }
   </style>