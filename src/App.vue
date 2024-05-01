<template>
  
    <div>
      <navigation-bar></navigation-bar>
    </div>
    <div>
      <investment-page></investment-page>
    </div>
    <div>
      <how-it-works></how-it-works>
    </div>
    <div>
      <projection-page></projection-page>
    </div>
    <div>
      <our-portfolio></our-portfolio>
    </div>
    <div>
      <!-- <investment-opportunities></investment-opportunities> -->
    </div>
    <div>
      <the-footer></the-footer>
    </div>
  
</template>

<script>
import NavigationBar from "./components/NavigationBar.vue";
import InvestmentPage from "./components/InvestmentPage.vue";
import HowItWorks from "./components/HowItWorks.vue";
import ProjectionPage from "./components/ProjectionPage.vue";
import OurPortfolio from "./components/OurPortfolio.vue";
import InvestmentOpportunities from "./components/InvestmentOpportunities.vue";
import TheFooter from "./components/TheFooter.vue";

export default {
  components: {
    NavigationBar,
    InvestmentPage,
    HowItWorks,
    ProjectionPage,
    OurPortfolio,
    InvestmentOpportunities,
    TheFooter,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Ubuntu&display=swap");
</style>