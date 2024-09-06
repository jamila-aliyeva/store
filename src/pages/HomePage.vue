<script setup>
import Header from "../components/header/index.vue";
import Footer from "../components/footer/index.vue";
import CreatingHome from "./CreatingHome.vue";

</script>

<template>
    <div class="container">
        <Header/>
        <div class="hero__bg">
            <div class="hero__content">
        <h2>Creative Home Simpify your Furniture</h2>
        <p>Do i have consent to record this meeting gain locaion, root-and-branch, review, nor game plan who’s the goto</p>
        <button>Shop Now</button>
          
        </div>
        </div>
    </div>
    <CreatingHome/>
    <Footer/>
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

@media only screen and (max-width:730px){
    .hero__content{
        h2{
            font-size: 46px;
        }
        p{
            font-size: 18px;
        }
    }
}
@media only screen and (max-width: 585px){
    header{
        background-position: right;
    }
    .hero__content{
        h2{
            font-size: 40px;
            line-height: 66px;
        }
        p{
            font-size: 16px;
            line-height: 28px;
        }
        button{
            padding: 10px 80px;
            font-size: 18px;
            margin-top: 40px;
        }
    }
}

@media only screen and (max-width: 488px){
    .hero__content{
        h2{
            font-size: 36px;
            line-height: 56px;
        }
        p{
            font-size: 15px;
            line-height: 26px;
        }
        button{
            padding: 9px 70px;
            font-size: 16px;
            margin-top: 30px;
        }
    }
}
@media only screen and (max-width: 400px){
    .hero__content{
        h2{
            font-size: 33px;
            line-height: 46px;
        }
        p{
            font-size: 15px;
            line-height: 22px;
        }
        button{
            padding: 9px 70px;
            font-size: 16px;
            margin-top: 30px;
        }
    }
}
@media only screen and (max-width: 312px){
    .hero__content{
        h2{
            font-size: 30px;
            line-height: 46px;
        }
        p{
            font-size: 15px;
            line-height: 22px;
        }
        button{
            padding: 9px 50px;
            font-size: 15px;
            margin-top: 40px;
        }
    }
}

</style>