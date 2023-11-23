<script>
export default {

}


</script>

<template>
   
    <section class="main-section">
        <h3> &LeftArrow; content goes here &rightarrow;</h3>
    </section>
    <section class=" main-section blue-section">
    
    </section>
    
</template>

<style lang="scss" scoped>
@use "../style/partials/mixin" as *;
@use "../style/partials/variables" as *;
.main-section {
    background-color: hsl(0deg 0% 10.98%);
    min-height: 200px;
    color: white;
}
.blue-section {
    background-color: $primary;
  
}

</style>