<script>
export default {
    
}
</script>

<template>
    <div>
        <div class="bg-texture">
            <div class="container">
                <div class="row">
                    <div class="col-12 text-center">
                        <p>AWARD WINNING</p>
                        <H2 class="abril-fatface-regular">Pro Barbers</H2>
                        <button><p>MEET YOUR NEW BARBER</p></button>
                    </div>
                </div>
            </div>
            <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#ffffff;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
        </div>
        <div class="bg-white">
            <div class="container">
                <div class="row">
                    <div class="col-12 text-center">
                        <p>MENS GROOMING</p>
                        <h2 class="abril-fatface-regular">Services</h2>
                    </div>
                    <div class="col-12 text-center">
                        <div class="row">
                            <div class="col-4">
                                <img src="../img/avadabarbers-trimcut-icon-before.png">
                                <h3 class="abril-fatface-regular">Trim & Cut</h3>
                                <div class="description">
                                    <p>Avada Barbers are experts in the lickety split trim and hair cut. Quick but careful and ridiculously good looking.</p>
                                </div>
                            </div>
                            <div class="col-4">
                                <img src="../img/avadabarbers-washndry-icon.png">
                                <h3 class="abril-fatface-regular">Wash & Dry</h3>
                                <div class="description">
                                    <p>Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashion.</p>
                                </div>
                            </div>
                            <div class="col-4">
                                <img src="../img/avadabarbers-beardtrim-icon.png">
                                <h3 class="abril-fatface-regular">Beard Tidy</h3>
                                <div class="description">
                                    <p>Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 text-center">
                        <button><p>READ ABOUT OUR SERVICES</p></button>
                    </div>
                </div>
            </div>
            <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#121315;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
            <div class="bg-image">
                <div class="container-fluid">
                    <div class="row">
                        <div class="col-12 text-center">
                            <p>WE HAVE YOU COVERED</p>
                            <h2 class="abril-fatface-regular">Avada Grooming Products</h2>
                        </div>
                        <div class="col-12 text-center">
                            <div class="row">
                                <div class="col-3">
                                    <img src="../img/brush_dark.png">
                                    <h4 class="abril-fatface-regular">Brush</h4>
                                    <p>$15.00</p>
                                </div>
                                <div class="col-3">
                                    <img src="../img/scissors.png">
                                    <h4 class="abril-fatface-regular">Scissors</h4>
                                    <p>$85.00</p>
                                </div>
                                <div class="col-3">
                                    <img src="../img/hot_oil_dark.png">
                                    <h4 class="abril-fatface-regular">Hot Oil</h4>
                                    <p>$15.00</p>
                                </div>
                                <div class="col-3">
                                    <img src="../img/straight_razor_dark.png">
                                    <h4 class="abril-fatface-regular">Straight Razor</h4>
                                    <p>$30.00</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 text-center">
                            <button><p>SHOP OUR PRODUCT RANGE</p></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.bg-texture{
    background-image: url(../img/avadabarbers-about-introbackground.jpg);
    background-size: cover;

    h2 {
    color: #b0b0b0;
    font-size: 70px;
    margin-bottom: 30px;
    }
    p{
        font-size: 18px;
        color: #be9359;
        font-weight: bold;
        margin: 100px 0px 0px 0px;
    }
    button{
        border: 3px solid #be9359;
        background-color: transparent;
        padding: 8px 30px;
        margin: 0px 0px 100px 0px;
        p{
            color: #be9359;
            font-size: 20px;
            font-weight: bold;
            margin: 0px;
        }
    }
}
.bg-white{
    background-color: white;

    h3{
        color: #be9359;
        font-size: 35px;
        margin: 30px 0px;
    }
    h2 {
        color: #b0b0b0;
        font-size: 60px;
        margin-bottom: 100px;
    }
    p{
        font-size: 18px;
        color: #be9359;
        font-weight: bold;
        margin: 0px;
    }
    button{
        border: 3px solid #be9359;
        background-color: transparent;
        padding: 8px 30px;
        margin: 0px 0px 100px 0px;
        p{
            color: #be9359;
            font-size: 20px;
            font-weight: bold;
            margin: 0px;
        }
    }
    .description{
        padding: 50px;
        margin-bottom: 35px;
        p{
            font-size: 18px;
            color: black;
            font-weight: 200;
        }
    }
    img{
        height: 120px;
    }
}
.abril-fatface-regular {
    font-family: "Abril Fatface", serif;
    font-weight: bolder;
    font-style: normal;

}
.bg-image{
    background-image: url(../img/avadabarbers-reviewsbackground.jpg);
    background-size: cover;
    .container-fluid{
        h2 {
            color: #b0b0b0;
            font-size: 70px;
            margin-bottom: 40px;
        }
        img{
            height: 400px;
            width: 400px;
        }
        h4{
            color: #be9359;
            font-size: 30px;
            margin: 15px 0px;
        }
        p{
            font-size: 18px;
            color: #be9359;
            font-weight: 200;
            margin: 0px 0px 80px 0px;
        }
        button{
        border: 3px solid #be9359;
        background-color: transparent;
        padding: 10px 35px;
        margin: 0px 0px 100px 0px;
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