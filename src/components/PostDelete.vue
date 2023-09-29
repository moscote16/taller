<template>
    <button class="post-delete">eliminar</button>
   </template>
   
   <script lang="ts">
        import{defineComponent, DefineComponent} from 'vue';
        export default defineComponent({
            name:"PostDelete"
        })
   </script>
   
   <style lang="scss" scoped>
        .post-button{
            background-color: rgb(68, 0, 255);
            padding: 3px;
            border: solid 1px rgb(0, 238, 255);
            &:hover{
                background-color: blue;
                border: solid px rgb(255, 0, 0);
                color: red;
            }
        }
   </style>