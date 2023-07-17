<template>
  <!-- ===============================================-->
    <!--    Main Content-->
    <!-- ===============================================-->
    <main class="main" id="top">
      <NavbarComponent></NavbarComponent>
      <hero-component></hero-component>
      <opportunity-component></opportunity-component>
      <invest-component></invest-component>
      <work-component></work-component>
      <review-component></review-component>

      <future-component></future-component>
        <FooterComponent></FooterComponent>
      
    </main><!-- ===============================================-->
    <!--    End of Main Content-->
    <!-- ===============================================-->
</template>
<script setup>
import FooterComponent from './section/FooterComponent.vue';
import NavbarComponent from './section/NavbarComponent.vue'
import HeroComponent from './section/HeroComponent.vue'
import OpportunityComponent from './section/OpportunityComponent.vue'
import InvestComponent from './section/InvestComponent.vue'
import WorkComponent from './section/WorkComponent.vue'
import ReviewComponent from './section/ReviewComponent.vue'
import FutureComponent from './section/FutureComponent.vue'
</script>
<style>
  @import '../assets/css/theme.min.css';
</style>
