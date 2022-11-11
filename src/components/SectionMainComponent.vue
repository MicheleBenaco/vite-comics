<template>
    <section class="bg-color-cont">
    <div class="container dflex section-cont ">
        <div class="dflex card">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="" class="img-shop"> 
            <h3>Digital Comics </h3>
        </div>

        <div class="dflex card">
            <img src="../assets/img/buy-comics-merchandise.png" alt="" class="img-shop">
            <h3>dc merchandise </h3>
        </div>

        <div class="dflex card">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="" class="img-shop">
            <h3>Subscription </h3>
        </div>

        <div class="dflex card">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="" class="img-shop">
            <h3>comics shop locator </h3>
        </div>
        
        <div class="dflex card">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="" class="img-shop">
            <h3>dc power visa  </h3> 
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
.card{
    margin-left: 50px;
}
.img-shop{
    width: 20%;    
}
h3{
    color: white;
    text-transform: uppercase;
    font-size: 14px;
    font-weight: 300;
    margin-left: 5px ;
    
}


</style>