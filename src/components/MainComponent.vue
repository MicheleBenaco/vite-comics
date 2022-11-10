<template>
    <main>
    <div class="container">
     <h1>Contenuti Qui </h1>
    </div>

   
     
    </main>
</template>

<script>
    export default {
        name:'MainComponent'
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/-variables.scss' as*;
@use '../assets/styles/general.scss' as*;
    main{
        background-color: $dark;

    }

    h1{
        color: white;
        padding: 30px;
    }
</style>