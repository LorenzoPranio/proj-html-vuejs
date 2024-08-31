<script>
export default {
    
}
</script>

<template>
    <div>
        <div class="bg-noir">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="row text-center">
                            <div class="col-4">
                                <img class="footer-img" src="../img/avadabarbers_footer_shop_image.png">
                                <button><p class="gold-text">SHOP OUR RANGE NOW</p></button>
                            </div>
                            <div class="col-4">
                                <img src="../img/avadabarbers-stickylogo-x2.png">
                                <ul>
                                    <li><p>Avada Barbers</p></li>
                                    <li><p>123 New York Street</p></li>
                                    <li><p>New York City</p></li>
                                    <li><p>info@yourwebsite.com</p></li>
                                    <li><p>+1 (555) 555-1212</p></li>
                                </ul>
                                <p class="gold-text mt-4">FOLLOW US</p>
                                <i class="fa-brands fa-facebook-f"></i>
                                <i class="fa-brands fa-twitter"></i>
                                <i class="fa-brands fa-youtube"></i>
                                <i class="fa-brands fa-instagram"></i>
                            </div>
                            <div class="col-4">
                                <img class="footer-img" src="../img/avadabarbers_footer_appointment_image.png">
                                <button><p class="gold-text">BOOK YOUR APPOINTMENT</p></button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-light-black">
            <div class="container">
                <div class="row">
                    <div class="col-12 text-center">
                        <p>&copy Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Right Reserved | Powered by WordPress</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .bg-noir{
        background-color: #121315;
        .col-4{
            margin-top: 60px;
            .footer-img{
                width: 450px;
            }
        }
        ul{
            list-style: none;
            margin-top: 50px;
            margin-bottom: 50px;
            padding: 0px;
            p{
                color: #b0b0b0;
                font-size: 18px;
                font-weight: 200;
                margin: 5px 0px;
            }
        }
        button{
            border: 3px solid #be9359;
            background-color: transparent;
            padding: 10px 35px; 
            margin-bottom: 100px;
            margin-top: 20px;
        }
        button:hover{
            transform: scale(1.1);
        }
        .gold-text{
            color: #be9359;
            font-size: 20px;
            font-weight: bold;
            margin: 0px;
        }
        .fa-brands{
            margin: 70px 10px 30px 10px;
            color: white;
            font-size: 22px;
        }
        .fa-brands:hover{
            color: #be9359;
        }
    }
    .bg-light-black{
        background-color: rgb(25, 25, 25);
        p{
            color: #b0b0b0;
            font-weight: 100;
            margin: 50px 0px;
            font-size: 14px;
        }
    }
</style>