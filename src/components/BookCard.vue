<script>
export default{
    props: {
    title: String,
    thumb: String,
    
  },
}
</script>

<template>
    <section>
    <div class="card">
      <img :src="thumb" alt="" />
      <h3>{{ title }}</h3>
    </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../style/partials/variables" as *;
@use "../style/partials/mixin" as *;

.card {

    height: 100%;}
 img {
        width: 100%;
        aspect-ratio: 1;
        object-fit: cover;
        object-position: top;
    }

    h3 {
        text-align: center;
        color: rgb(0, 0, 0);
    }
</style>