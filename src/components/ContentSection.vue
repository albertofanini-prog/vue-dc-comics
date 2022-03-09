<template>
    <div class="content_section">
        <div class="content_section-container">
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
            <div class="card_wrapper">
                <div class="card_img">
                    img
                </div>
                <div class="card_title">
                    text
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ContentSection',
}
</script>

<style lang="scss" scoped>
    .content_section{
        background-color: #232325;
        width: 100%;
        height: 500px;
        display: flex;
        align-items: center;
        .content_section-container{
            width: 70%;
            border: 5px solid orange;
            height: 95%;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            align-items: center;
            .card_wrapper{
                width: 15%;
                height: 40%;
                border: 3px solid blue;
                display: flex;
                flex-direction: column;
                align-items: center;
                .card_img{
                    width: 100%;
                    height: 85%;
                    border: 1px solid red;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                }
                
                .card_title{
                    width: 100%;
                    height: 15%;
                    border: 1px solid yellow;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                }
            }
        }
    }
</style>