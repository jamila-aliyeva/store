<script setup>

</script>

<template>
    <div class="container">
        <div class="creating__wrapper">
        <div class="creating__img">
           <img src="../assets/models.png" alt="">
        </div>
        <div class="creating__content">
          <h2 class="creating__title">We Create your home more aestetic</h2>
          <p class="creating__pr">Furnitre power is a software as services for multiperpose business management system</p>
             <div class="creating__info">
               <span class="material-symbols-outlined">check_circle</span>
              <div class="creating__text">
                <h4>Valuation Services</h4>
                <p>Sometimes features require a short description. This can be detailed description</p>
              </div>
             </div>

             <div class="creating__info">
               <span class="material-symbols-outlined">check_circle</span>
              <div class="creating__text">
                <h4>Valuation Services</h4>
                <p>Sometimes features require a short description. This can be detailed description</p>
              </div>
             </div>
        </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.creating__wrapper{
    margin-block: 200px;
    width: 100%;
    column-gap: 100px;
    align-items: center;
    display: flex;
    justify-content: center;
}
.creating__img{
    max-width: 554px;
    height: 443px;
    img{
        border-radius: 10px;
        width: 100%;
        height: 100%;
    }
}
.creating__title{
    font-size: 40px;
    font-weight: 600;
    max-width: 508px;
    text-transform: capitalize;
}
.creating__pr{
    margin-block: 30px;
    font-size: 20px;
    font-weight: 400;
    line-height: 34px;
    max-width: 587px;
}
.creating__info{
    display: flex;
    column-gap: 15px;
    span{
        margin-top: 4px;
        font-size: 28px;
    }
    .creating__text{
        h4{
            font-size: 22px;
            font-weight: 700;
        }
        p{
            font-size: 16px;
            margin-top: 5px;
            max-width: 530px;
        }
    }
}
@media only screen and (max-width:1000px){
    .creating__wrapper{
        padding: 0 1rem;
    }
    .creating__content{
        h2{
            font-size: 36px;
            max-width: 480px;
        }
            p{
            font-size: 18px;
            line-height: 30px;
            max-width: 450px;
        }
        
    }
    .creating__info{
        column-gap: 10px;
        span{
                font-size: 24px;
            }
            
    }
    .creating__text{
        h4{
            font-size: 20px;
                    font-weight: 600;
        }
        p{
                    line-height: 26px;
                }
    }
    

}
@media only screen  and (max-width:810px){
    .creating__wrapper{
        flex-direction: column-reverse;
        align-items: center;
        .creating__img img{
        margin-top: 45px;
    }
    }

    .creating__content{
        h2{
            font-size: 40px;
            max-width: 550px;
        }
        p{
            max-width: 530px;
            font-size: 18px;
            line-height: 26px;
        }
    }

    
}
@media only screen  and (max-width:510px){
    .creating__content{
        h2{
            font-size: 30px;
        }
    }
    
}

</style>