<template>
    <div class="jumbo-cont">
        <img src="../assets/img/jumbotron.jpg" alt="">
    </div>
</template>

<script>
    export default {
        name:'JumbotronComponent'
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/-variables.scss' as*;
@use '../assets/styles/general.scss' as*;
.jumbo-cont{
    position: relative;
    padding-bottom: 30.25%; /* 16:9 ratio */
    height: 0px;
    overflow: hidden;
   img{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
   }
}


</style>