<template>
    <div class="social_bar">
        <div class="social_button">    
            <button>
                sign-up now!
            </button>
        </div>
        <div class="social_icons">
            <h6>follow us</h6>
            <img v-for="(social, i) in socials" :key="i" :src="social.src">
        </div>
    </div>
</template>

<script>
export default {
    name: 'SocialBar',
    data(){
        return{
            socials: [
                {
                    src: require('../assets/img/footer-facebook.png'),
                },
                {
                    src: require('../assets/img/footer-twitter.png'),
                },
                {
                    src: require('../assets/img/footer-youtube.png'),
                },
                {
                    src: require('../assets/img/footer-periscope.png'),
                },
                {
                    src: require('../assets/img/footer-pinterest.png'),
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .social_bar{
        height: 105px;
        background-color: #303030;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        padding: 0px 3%;
        .social_button{
            width: 50%;
            text-align: left;
            button{
                padding: 10px;
                background-color: transparent;
                border: 1px solid #0D7DEC;
                color: white;
                text-transform: uppercase;
            }
        }
        .social_icons{
            color: #0D7DEC;
            text-transform: uppercase;
            font-size: 22px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 20px;
        }
    }
    
</style>