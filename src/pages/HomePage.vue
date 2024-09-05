<script setup>
import Header from "../components/header/index.vue";
</script>

<template>
        <Header/>
    <div class="container">
        <div class="hero__bg">
            <div class="hero__content">
        <h2>Creative Home Simpify your Furniture</h2>
        <p>Do i have consent to record this meeting gain locaion, root-and-branch, review, nor game plan who’s the goto</p>
        <button>Shop Now</button>
          
        </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
.hero__bg{
    display: grid;
    place-items: center;
    width: 100%;
    min-height: 850px;
    background-image: url(../assets/hero_banner.png);
    background-size: cover;
    background-position: center;
}
.hero__content{
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    h2{
        color: #fff;
        font-size: 64px;
        line-height: 76px;
        font-weight: 600;
        letter-spacing: 0.2px;
        max-width: 880px;
        text-align: center;
    }
    p {
        margin-top: 30px;
        color: #fff;
        font-size: 20px;
        line-height: 30px;
        max-width: 620px;
        text-align: center;
        letter-spacing: 0.2px;
    }
    button {
        border-radius: 10px;
        margin-top: 60px;
        padding: 10px 90px;
        color: #fff;
        font-size: 20px;
        border: none;
        letter-spacing: 0.2px;
        font-weight: 600;
        background-color: rgba(226, 226, 226, 0.4);
    }
}

</style>