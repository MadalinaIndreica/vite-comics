<script>
export default {

}


</script>

<template>
   

    <section class=" main-section blue-section">
     <div class="main-icons container ">
        <div>
            <img class="smaller" src="../assets/img/buy-comics-digital-comics.png" alt="">
            <h4>DIGITAL COMICS</h4>
        </div>
        <div>
            <img class="normal" src="../assets/img/buy-comics-merchandise.png" alt="">
            <h4>DC MERCHANDISE</h4>
        </div>
        <div>
            <img class="normal" src="../assets/img/buy-comics-subscriptions.png" alt="">
            <h4>SUBSCRIPTION</h4>
        </div>
        <div>
            <img  class="smaller" src="../assets/img/buy-comics-shop-locator.png" alt="">
            <h4>COMIC SHOP LOCATOR</h4>
        </div>
        <div>
            <img  class="normal" src="../assets/img/buy-dc-power-visa.svg" alt="">
            <h4>DC POWER VISA</h4>
        </div>

     </div>
    </section>
    
</template>

<style lang="scss" scoped>
@use "../style/partials/mixin" as *;
@use "../style/partials/variables" as *;

.blue-section {
    background-color: $primary;
    color: white;
    .main-icons {
        padding: 3rem;
        @include  flex();
        justify-content: space-between;
        div {
            @include  flex();
            font-family : monospace;

        }
       .normal {
        width: 50px;
        margin-right: 15px;
        margin-left: 10px;
            
       }
       .smaller {
                width: 30px;
                margin-right: 15px;
                margin-left: 10px;
            }
       
    }
  
}

</style>