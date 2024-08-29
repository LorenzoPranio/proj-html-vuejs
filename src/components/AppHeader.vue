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
            <div class="row">
                <div class="col-6">
                    <h1 class="abril-fatface-regular">Barber Shop</h1>
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
        }

    }
</style>