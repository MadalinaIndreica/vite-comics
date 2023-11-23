<script>
export default {

}

</script>

<template>
    <footer>
       
            <section class="footer footer-top">
                <div class="listItem">
                    <h4>CD COMICS</h4>
                    <ul>
                        <li>character</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>games</li>
                        <li>TV</li>
                        <li>videos</li>
                        <li>news</li>

                    </ul>
                </div>
                <div class="listItem">
                    <h4>DC</h4>
                    <ul>
                        <li>character</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>games</li>
                        <li>TV</li>
                        <li>videos</li>
                        <li>news</li>
                        <li>character</li>
                        <li>comics</li>
                        <li>movies</li>

                    </ul>
                </div>
                <div class="listItem">
                    <h4>SITES</h4>
                    <ul>
                        <li>character</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>games</li>
                        <li>TV</li>


                    </ul>
                </div>
                <div class="listItem">
                    <h4>SHOP</h4>
                    <ul>
                        <li>shop dc</li>
                        <li>shop dc collectibles</li>

                    </ul>
                </div>

            </section>
            <section class="footer footer-bottom">
               
                <button>SING-UP NOW!</button>
                <div class="footer-icons">
                    <h3>FOLLOW US</h3>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
               

            </section>
      

    </footer>
</template>

<style lang="scss" scoped>
@use "../style/partials/mixin" as *;
@use "../style/partials/variables" as *;

footer {
    color: white;
    background-image: url(../assets/img/footer-bg.jpg);
    min-height: 300px;


    .footer-top {
        @include flex ();
        align-items: left;
        justify-content: flex-start;

        .listItem {
            min-height: 280px;
            padding: 1rem;
            margin-top: 1rem;
        }

        h4 {
            text-align: center;
        }

        ul {
            margin-top: 2rem;
            color: darkgray;
            list-style: none;

        }
    }

    .footer-bottom {
        background-color: hsl(0deg 0% 18.82%);
        min-height: 100px;
        @include flex ();
        justify-content: space-between;
        padding: 2rem;


 
        button {
            background-color: hsl(0deg 0% 18.82%);
            border: 2px solid $primary;
            padding: 10px;
            color: white;
        }

        .footer-icons {
            @include flex ();
            gap: 1rem;

            h3 {
                color: $primary;
            }

        }
    }


}</style>