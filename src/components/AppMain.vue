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
                        <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#ffffff;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
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

</style>