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
                        <h2>Services</h2>
                    </div>
                    <div class="col-12 text-center">
                        <div class="row">
                            <div class="col-4">
                                <img src="../img/avadabarbers-trimcut-icon-before.png">
                                <h3>Trim & Cut</h3>
                                <p>Avada Barbers are experts in the lickety split trim and hair cut. Quick but careful and ridiculously good looking.</p>
                            </div>
                            <div class="col-4">
                                <img src="../img/avadabarbers-washndry-icon.png">
                                <h3>Wash & Dry</h3>
                                <p>Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashion.</p>
                            </div>
                            <div class="col-4">
                                <img src="../img/avadabarbers-beardtrim-icon.png">
                                <h3>Beard Tidy</h3>
                                <p>Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 text-center">
                        <button><p>READ ABOUT OUR SERVICES</p></button>
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

    .abril-fatface-regular {
    font-family: "Abril Fatface", serif;
    font-weight: bolder;
    font-style: normal;
    color: #b0b0b0;
    font-size: 70px;
    margin-bottom: 30px;
    }
    p{
        font-size: 15px;
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
}

</style>