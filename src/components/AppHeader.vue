<script>
export default {

}
</script>

<template>
    <div class="bg-head">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="row">
                        <div class="col-6 pt-4">
                            <img src="../img/avadabarbers-logo-x2-200x70.png">
                        </div>
                        <div class="col-6 text-end pt-4">
                            <i class="fa-solid fa-cart-shopping"></i>
                            <i class="fa-solid fa-bars"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row align-items-center">
                <div class="col-6">
                    <h1 class="abril-fatface-regular">Barber Shop</h1>
                    <hr>
                    <p>The Pinnacle of Male Grooming</p>
                    <button><p>LEARN MORE</p></button>
                </div>
                <div class="col-6">
                    <img src="../img/avadabarbers_hero_focalmirror-600x825.png">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .bg-head{
        background-image: url('../img/avadabarbers-homepage-hero-bg.jpg');
        height: 1000px;
        background-size: cover;
        
        .fa-solid{
            color: white;
            margin: 10px;
            font-size: x-large;
        }
        .abril-fatface-regular {
            font-family: "Abril Fatface", serif;
            font-weight: bolder;
            font-style: normal;
            color: white;
            font-size: 90px;
            margin-bottom: 30px;
        }
        .col-6{
            hr{
                color: #be9359;
                border: 3px solid #be9359;
                opacity: 1;
                width: 270px;
            }
            p{
                font-size: 25px;
                color: #b0b0b0;
                font-weight: 100;
                margin: 40px 0px;
            }
            button{
                border: 3px solid #be9359;
                background-color: transparent;
                padding: 10px 35px;
                p{
                    color: #be9359;
                    font-size: 20px;
                    font-weight: bold;
                    margin: 0px;
                }
            }
        }
    }
</style>