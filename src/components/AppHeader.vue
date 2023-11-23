<script>
export default {
    data() {
    return {
      navItems: [
        {
          title: "CHARACTERS",
          isActive: false,
        },
        {
          title: "COMICS",
          isActive: true,
        },
        {
          title: "MOVIES",
          isActive: false,
        },
        {
          title: "TV",
          isActive: false,
        },
        {
          title: "GAMES",
          isActive: false,
        },
        {
          title: "COLLECTIBLES",
          isActive: false,
        },
        {
          title: "VIDEOS",
          isActive: false,
        },
        {
          title: "FANS",
          isActive: false,
        },
        {
          title: "NEWS",
          isActive: false,
        },
        {
          title: "SHOP",
          isActive: false,
        },
      ],
    };
  },
};



</script>

<template>
    <header>
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="logo">
        </div>
        <ul>
            <li v-for="item in navItems" :key="item.title">
                <a :class="{ active: item.isActive }" href="">{{ item.title }}</a>
            </li>
        
        </ul>
    </header>

  
</template>

<style lang="scss" scoped>
@use "../style/partials/mixin" as *;
@use "../style/partials/variables" as *;
header{
    @include flex();
    justify-content: space-between;
    padding: 2rem;
   img {
    width: 70px;
   }
   
    ul { 
        @include flex();
        list-style-type:  none;
        gap: .5rem;
        a {
            padding: .5rem;
            text-decoration: none;
            color: black;

            &:hover {
                background-color: lightblue;
            }
            &.active {
                border-bottom: 5px  solid $primary;
            }
        }


    }
}


</style>
