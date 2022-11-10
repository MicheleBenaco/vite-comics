<template>
    <div class="bg-color">
        <div class="container cont-fin">
            <a href="#" class="standard-btn btn-lg">SIGN-UP NOW </a>
            <div class="follow-us">
                <h3>FOLLOW US </h3>
                <img src="../assets/img/footer-facebook.png" alt="" class="space">
                <img src="../assets/img/footer-twitter.png" alt="" class="space">
                <img src="../assets/img/footer-pinterest.png" alt="" class="space">
                <img src="../assets/img/footer-youtube.png" alt="" class="space">
                <img src="../assets/img/footer-periscope.png" alt="" class="space">
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name:'SingUpComponent',
        
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/-variables.scss' as*;
@use '../assets/styles/general.scss' as*;
.bg-color{
    background-color: rgb(48, 48, 48);
    height: 200px;
    width: 100%;
    position: absolute;
    z-index: 1000;
}

.space{
    margin: 10px;
}

.cont-fin{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.follow-us{
    padding-top: 50px;
    display: flex;
    align-items: center;
   
}
.standard-btn {
  text-decoration:none;
  border: 2px solid $blue;
  padding:10px 20px 10px 20px;
  border-radius:2px;
  color:#fafbfb;
  margin-top: 50px;
}
.standard-btn-coloured {
  text-decoration:none;
  background:$blue;
  border: 2px solid $blue;
  padding:10px 20px 10px 20px;
  border-radius:2px;
  color:#FFFFFF;
  margin:5px;
}
.standard-btn:hover {
  color:#FFFFFF;
  background-color:$blue;
}
.standard-btn-coloured:hover {
  color:#FFFFFF;
  background-color:$blue;
}

</style>