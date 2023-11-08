<template>
  <div id="app">
    <div class="background_container" id="about">
      <div class="wrapper">
        <header-app/>

        <promo-app/>

        <about-me-app/>

        <portfolio-app/>

        <technologies-app/>

        <career-app/>

        <recommend-app/>

        <contacts-app/>

      </div>
    </div>
    <footer class="footer">
      <footer-app/>
    </footer>
  </div>
</template>

<script>

import HeaderApp from "@/components/HeaderApp.vue";
import PromoApp from "@/components/PromoApp.vue";
import AboutMeApp from "@/components/AboutMeApp.vue";
import PortfolioApp from "@/components/PortfolioApp.vue";
import TechnologiesApp from "@/components/TechnologiesApp.vue";
import CareerApp from "@/components/CareerApp.vue";
import RecommendApp from "@/components/RecommendApp.vue";
import ContactsApp from "@/components/ContactsApp.vue";
import FooterApp from "@/components/FooterApp.vue";

export default {
  components: {
    FooterApp,
    ContactsApp, RecommendApp, CareerApp, TechnologiesApp, PortfolioApp, HeaderApp, PromoApp, AboutMeApp}

}
</script>

<style lang="scss">

</style>
