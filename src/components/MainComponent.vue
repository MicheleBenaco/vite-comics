<template>
    <main>
    <div class="container">
        <div class="row">
            <ComicsComponent v-for="(comic,index) in comics" :key="index"/>
        </div>

    </div>

   
     
    </main>
</template>

<script>
import comics from '../data/comics.js';
import ComicsComponent from './ComicsComponent.vue';

    export default {
    name: "MainComponent",
    components: { ComicsComponent }
}
</script>

<style lang="scss">
@use '../assets/styles/partials/-variables.scss' as*;
@use '../assets/styles/general.scss' as*;
    main{
        background-color: $dark;
        
        h1{
        color: white;
        padding: 30px;
    }

    .row{
        display: flex;
        .col{
            flex-basis: calc(100% / 6);
            padding: 10px;

           
        }

    }
        
    }

   


</style>