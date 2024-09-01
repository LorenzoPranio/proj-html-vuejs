<script>
import AppCopy from './AppCopy.vue';
export default {
  components: {
    AppCopy
  },
  data() {
    return {
      contactInfo: [
        { text: 'Avada Barbers' },
        { text: '123 New York Street' },
        { text: 'New York City' },
        { text: 'info@yourwebsite.com' },
        { text: '+1 (555) 555-1212' }
      ],
      socialIcons: [
        { iconClass: 'fa-facebook-f' },
        { iconClass: 'fa-twitter' },
        { iconClass: 'fa-youtube' },
        { iconClass: 'fa-instagram' }
      ],
      footerSections: [
        {
          imgSrc: "/src/img/avadabarbers_footer_shop_image-400x312.png",
          buttonText: "SHOP OUR RANGE NOW"
        },
        {
          imgSrc: "/src/img/avadabarbers-stickylogo-x2.png",
          ContactSection: true
        },
        {
          imgSrc: "/src/img/avadabarbers_footer_appointment_image-400x312.png",
          buttonText: "BOOK YOUR APPOINTMENT"
        }
      ]
    };
  }
};

</script>

<template>
    <div>
        <div class="bg-noir">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="row text-center">
                            <div class="col-4" v-for="(section, index) in footerSections" :key="index">
                                <img :src="section.imgSrc">
                                <template v-if="section.ContactSection">
                                    <ul>
                                        <li v-for="(item, index) in contactInfo" :key="index">
                                            <p>{{ item.text }}</p>
                                        </li>
                                    </ul>
                                    <p class="gold-text mt-4">FOLLOW US</p>
                                    <a v-for="(icon, index) in socialIcons" :key="index" :href="icon.link">
                                        <i :class="['fa-brands', `${icon.iconClass}`]"></i>
                                    </a>
                                </template>
                                <template v-else>
                                    <button><p class="gold-text">{{ section.buttonText }}</p></button>
                                </template>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <AppCopy />
    </div>
</template>

<style lang="scss" scoped>
    .bg-noir{
        background-color: #121315;
        .col-4{
            margin-top: 60px;
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
            margin-top: 40px;
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
            margin: 50px 10px 30px 10px;
            color: white;
            font-size: 22px;
        }
        .fa-brands:hover{
            color: #be9359;
        }
    }
</style>