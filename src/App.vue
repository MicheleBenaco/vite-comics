<template>
  <HeaderComponent/>
  <MainComponent/>
  <SectionMainComponent/>
  <FooterComponent/>
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import SectionMainComponent from './components/SectionMainComponent.vue';


  export default {
    components: { HeaderComponent, MainComponent, SectionMainComponent, FooterComponent }
}
</script>

<style lang="scss" scoped>

</style>