<template>
    <section class="bg-color-cont">
    <div class="container dflex ">
        <div class="dflex">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" class="img-shop"> 
        <h3>Digital Comics </h3>
        </div>

        <div class="dflex">
        <img src="../assets/img/buy-comics-merchandise.png" alt="" class="img-shop">
        <h3>Digital Comics </h3>
        </div>

        <div class="dflex">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="" class="img-shop">
        <h3>Digital Comics </h3>
        </div>

        <div class="dflex">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="" class="img-shop">
        <h3>Digital Comics </h3>
        </div>
        <div class="dflex">
            <div class="conteiner-svg">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="" class="img-shop">
            </div><h3>Digital Comics </h3>
            
        </div>
        
    </div>
    </section>
    
</template>

<script>
    export default {
        name:'SectionMainComponent'
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/-variables.scss' as*;
@use '../assets/styles/general.scss' as*;

.bg-color-cont{
    display: flex;
    justify-content: center;
    background-color: $blue;
    height: 200px;
}
.conteiner-svg{
    width: 50%;
    display: inline-block;
    padding: 0;
    margin: 0;

}
.img-shop{
    width: 20%;
}

</style>