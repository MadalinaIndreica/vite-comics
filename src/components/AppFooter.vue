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



}
</style>