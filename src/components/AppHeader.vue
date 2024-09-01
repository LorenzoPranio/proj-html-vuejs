<script>
    export default {
        data() {
    return {
      OpenMenu: false,
      menuItems: [
        { name: 'Home', link: '#' },
        { name: 'About Us', link: '#' },
        { name: 'Services', link: '#' },
        { name: 'Shop', link: '#' },
        { name: 'Our Team', link: '#' },
        { name: 'Blog', link: '#' },
        { name: 'Contact Us', link: '#' }
      ]
    };
  },
  methods: {
    PopupMenu() {
      this.OpenMenu = !this.OpenMenu;
    }
  }
};
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
                            <i class="fa-solid fa-bars" @click="PopupMenu"></i>
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
        <!-- Popup Menu -->
        <div v-if="OpenMenu" class="popup-menu">
            <div class="menu-header">
                <i class="fa-solid fa-xmark" @click="PopupMenu"></i>
            </div>
            <ul class="menu-list">
                <li v-for="item in menuItems" :key="item.name">
                    <a :href="item.link">{{ item.name }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .bg-head{
        background-image: url('../img/avadabarbers-homepage-hero-bg.jpg');
        height: 1000px;
        background-size: cover;
        position: relative;
        
        .fa-solid{
            color: white;
            margin: 10px;
            font-size: x-large;
        }
        .fa-solid:hover{
            cursor: pointer;
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
            button:hover{
                transform: scale(1.1);
            }
        }
    }
    //Popup Menu
    .popup-menu {
        position: absolute;
        top: 0;
        right: 0;
        width: 100%;
        height: 100%;
        background-color: black;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        z-index: 1;
        padding-top: 20px;
    }

    .menu-header {
        position: absolute;
        top: 20px;
        right: 20px;
    }

    .menu-header i {
        color: white;
        font-size: 24px;
        cursor: pointer;
    }
    .menu-header i:hover{
        color: #be9359;
    }

    .menu-list {
        list-style: none;
        padding: 0;
        text-align: center;
    }

    .menu-list li {
        margin: 30px 0px;
    }

    .menu-list li a {
        text-decoration: none;
        color: white;
        font-size: 24px;
    }
    .menu-list li a:hover{
        color: #be9359;
        font-weight: 700;
    }
</style>