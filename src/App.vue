<script>
import AppHeader from "./components/AppHeader.vue";
import AppIcons from "./components/AppIcons.vue";
import AppFooter from "./components/AppFooter.vue";
import AppJumbotron from "./components/AppJumbotron.vue";
import CurrentSeries from "./components/CurrentSeries.vue"

export default {
  components: {
    AppHeader,
    AppJumbotron,
    CurrentSeries,
    AppIcons,
    AppFooter
},
};

</script>

<template>
  <div class="container">
    <AppHeader/>
  </div>
    <AppJumbotron/>
    <CurrentSeries/>
    <AppIcons />
  
    <AppFooter />
  

  
</template>

<style lang="scss">
@use "./style/general.scss";

.container{
  width: 80%;
  margin: 0 auto;
}


</style>
