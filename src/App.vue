<template>
  <HeaderComponent/>
  <JumbotronComponent/>
  <MainComponent/>
  <SectionMainComponent/>
  <FooterComponent/>
  <SignUpComponent/>
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import MainComponent from './components/MainComponent.vue';
import SectionMainComponent from './components/SectionMainComponent.vue';
import SignUpComponent from './components/SignUpComponent.vue';


  export default {
    components: { HeaderComponent, MainComponent, SectionMainComponent, FooterComponent, SignUpComponent, JumbotronComponent }
}
</script>

<style lang="scss" scoped>

</style>