<template>
  <HeaderComponent/>
  <MainComponent/>
  <SectionMainComponent/>
  <FooterComponent/>
  <SignUpComponent/>
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import SectionMainComponent from './components/SectionMainComponent.vue';
import SignUpComponent from './components/SignUpComponent.vue';


  export default {
    components: { HeaderComponent, MainComponent, SectionMainComponent, FooterComponent, SignUpComponent }
}
</script>

<style lang="scss" scoped>

</style>