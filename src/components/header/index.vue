<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
    <div class="container">
    <nav>
        <div class="nav__wrapper">
        <div class="nav__logo">
            
        <img src="../../assets/logo.svg" alt="">
        </div>
        <ul class="nav__menu">
        <li><a class="item-link" href="">Home</a></li>
        <li><a class="item-link" href="">Products</a></li>
        <li><a class="item-link" href="">Features</a></li>
        <li><a class="item-link" href="">Contact</a></li>
        </ul>
        <div class="nav__actions">
           <RouterLink class="nav__action__link" to="/"><span class="material-symbols-outlined">account_circle</span><strong>Account</strong></RouterLink>
           <RouterLink class="nav__action__link" to="/"><span class="material-symbols-outlined">favorite</span> <strong>Favourite</strong></RouterLink>
           <RouterLink class="nav__action__link" to="/"><span class="material-symbols-outlined">shopping_cart</span> <strong>Cart</strong></RouterLink>
        </div>
        </div>
   

    </nav>
</div >
</template>



<style lang="scss" scoped>

nav{
    margin-top: 20px;
    height: 40px;
    position: absolute;
    z-index: 2 !important;
}
.nav__wrapper{
    display: flex;
    align-items: center;
    // justify-content: space-between;
    gap: 100px;
    width: 100%;
}
.nav__menu{
    display: flex;
    align-items: center;
    column-gap: 64px;
    list-style-type: none;
    color: #fff;
    transform-origin: top ;
     .item-link{
        font-size: 18px;
        font-weight: 400;
        transition: 0.2s;
        color: #fff;
        text-decoration: none;

        &:hover {
            opacity: 0.8;
        }
    }

}
.nav__logo{
    padding-left: 30px;
}
.nav__actions{
    display: flex;
    align-items: center;
    column-gap: 30px;
    .nav__action__link{
        display: flex;
        align-items: center;
        column-gap: 5px;
        color: #fff;
        &:hover{
            opacity: 0.8;
        }
        strong{
            font-weight: 500;
        font-size: 16px;
        letter-spacing: 0.9px;
        }
        span{
            font-size: 21px;
        }
    }
}

</style>