<template>
    <div class="col">
        <img :src="img">
        <h4>{{price}} </h4>
        <h4>{{series}}</h4>
        <h4>{{type}}</h4>
    </div>

</template>

<script>
    export default {
        name:'ComicsComponent',
        props:[
            'img','price','series','type'
        ]
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/-variables.scss' as*;
@use '../assets/styles/general.scss' as*;




</style>