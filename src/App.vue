<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";


export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
},
};

</script>

<template>
  <div class="container">
    <AppHeader/>
  </div>
  
    <AppMain />
  
    <AppFooter />
  

  
</template>

<style lang="scss">
@use "./style/general.scss";

.container{
  width: 80%;
  margin: 0 auto;
}


</style>
