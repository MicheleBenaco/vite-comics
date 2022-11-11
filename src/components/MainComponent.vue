<template>
    <main>
    <div class="container">
        <div class="row">
            <ComicsComponent v-for="(comic,index) in comics" :key="index" 
            :img="comic.thumb" :price="comic.price" :series="comic.series" :type="comic.type" />
        </div>

    </div>

   
     
    </main>
</template>

<script>
import {data_comics} from '../data/comics.js';
import ComicsComponent from './ComicsComponent.vue';

    export default {
    name: "MainComponent",
    components: { ComicsComponent },
    data(){
        return{
            comics: data_comics,
        }
    }
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
        flex-wrap: wrap;
        margin-top: 20px;
        margin-bottom: 20px;

        .col{
           
            flex-basis: calc(100% /6);
            padding: 9px;

            h4{
                color: white;
                padding: 5px;
            }
           
        }

    }
        
    }

   


</style>