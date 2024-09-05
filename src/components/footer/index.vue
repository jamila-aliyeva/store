<script setup>

</script>

<template>
    <footer>
    <div class="container">
    <div class="footer__wrapper">
    
    <div class="footer__header">
    <img src="../../assets/logo.svg" alt="Logo">
     <div class="footer__socials">
       <div>
        <img src="../../assets/instagram.svg" alt="">
       <img src="../../assets/facebook.svg" alt="">
       <img src="../../assets/github.svg" alt="">
       <img src="../../assets/twitter.svg" alt="">
       <img src="../../assets/.svg" alt=""></div>
     </div>
    </div>

     <div class="footer__menu-container">
        <ul>
            <li>Our Products</li>
            <li>The Support Suite</li>
            <li>The Sales Suite</li>
            <li>Support</li>
            <li>Guide</li>
        </ul>
        <ul>
            <li>Top Features</li>
            <li>Ticketing System</li>
            <li>Knowledge Base</li>
            <li>Community Forums</li>
            <li>Help Desk Software</li>
        </ul>
        <ul>
            <li>Resources</li>
            <li>Product Support</li>
            <li>Request Demo</li>
            <li>Library</li>
            <li>Peoplepower Blog</li>
        </ul>
        <ul>
            <li>Company</li>
            <li>About Us</li>
            <li>Press</li>
            <li>Investors</li>
            <li>Events</li>
        </ul>
        <ul>
            <li>Favourite Things</li>
            <li>For Enterprise</li>
            <li>For Startups</li>
            <li>For Benchmark</li>
            <li>For Small Business</li>
        </ul>
     </div>
     <p class="copyright-text">© NameBrand 2022 - All Rights Reserved</p>
    
    

    </div>
    </div>
    </footer>

</template>

<style lang="scss" scoped>
footer{
    padding: 60px 0 20px;
    width: 100%;
    background-color: #23262F;
}
.footer__header{
  width: 100%;
  max-width: 1200px;
  padding:0 10px 60px;
   margin: auto;
  display: flex;
  justify-content: space-between;
}
.footer__socials div{
    display: flex;
    column-gap: 10px;
}


.footer__menu-container{
        margin-top:64px;
        width: 100%;
        max-width: 1200px;
        margin: auto;
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        padding: 20px;

        ul{
            display: flex;
            flex-direction: column;
            row-gap: 15px;
            li{
                font-size: 15px;
                color: #fff;
                font-weight: 500;
            }
            li:first-child{
                font-size: 18px ;
            }
        }
}

.copyright-text{
        margin-top: 70px;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        text-align: center;
    }


</style>