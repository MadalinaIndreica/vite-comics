<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";


export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppHeader
},
};

</script>

<template>
  <div class="container">
    <AppHeader/>
    <AppMain />
    <AppFooter />
  </div>
  
</template>

<style lang="scss">
@use "./style/general.scss";
.container {
  width: 80%;
  margin: 0 auto;
}

</style>
