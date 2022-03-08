<template>
    <div class="blue_section">
        <ul>
            <li>
                <div class="blue_section_item-img">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                <div class="blue_section_item-text">
                    digital comics
                </div>
            </li>
            <li>
                <div class="blue_section_item-img">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                <div class="blue_section_item-text">
                    dc merchandise
                </div>
            </li>
            <li>
                <div class="blue_section_item-img">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                <div class="blue_section_item-text">
                    sbuscription
                </div>
            </li>
            <li>
                <div class="blue_section_item-img">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <div class="blue_section_item-text">
                    comic shop location
                </div>
            </li>
            <li>
                <div class="blue_section_item-img">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                <div class="blue_section_item-text">
                    dc power visa
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'BlueSection',
  props: {
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