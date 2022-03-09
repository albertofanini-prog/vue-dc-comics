<template>
    <div class="blue_section">
        <ul>
            <li v-for="(blueItem, i) in blueItems" :key="i">
                <div class="blue_section_item-img">
                    <img :src="blueItem.src" alt="">
                </div>
                <div class="blue_section_item-text">
                    {{blueItem.text}}
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'BlueSection',
    data(){
        return{
            blueItems:[
                {
                    text: 'digital comics',
                    src: require('../assets/img/buy-comics-digital-comics.png'),
                },
                {
                    text: 'dc merchandise',
                    src: require('../assets/img/buy-comics-merchandise.png'),
                },
                {
                    text: 'subscription',
                    src: require('../assets/img/buy-comics-shop-locator.png'),
                },
                {
                    text: 'comic shop location',
                    src: require('../assets/img/buy-comics-shop-locator.png'),
                },
                {
                    text: 'dc power visa',
                    src: require('../assets/img/buy-dc-power-visa.svg'),
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .blue_section{
        background-color: #0D7DEC;
        width: 100%;
        padding: 30px 0px;
        ul{
            height: 100%;
            list-style: none;
            display: flex;
            align-items: center;
            padding: 0px 10%;
            li{
                width: 19%;
                display: flex;
                justify-content: center;
                align-items: center;
                gap: 5px;
                .blue_section_item-img{
                    width: 20%;
                    // border: 1px solid black;
                    img{
                        width: 50px;
                        height: 60px;
                    }
                }
                .blue_section_item-text{
                    width: 80%;
                    // border: 1px solid black;
                    text-transform: uppercase;
                    color: white;
                    text-align: left;
                }
            }
        }
    }
</style>