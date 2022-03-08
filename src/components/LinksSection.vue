<template>
    <div class="links_section">
        <div class="link_section_items">
            <ul>
                <h6 id="link_section_title">
                    dc comics
                </h6>
                <li>
                    <span>
                        Characters
                    </span>
                </li>
                <li>
                    <span>
                        Comics
                    </span>
                </li>
                <li>
                    <span>
                        Movies
                    </span>
                </li>
                <li>
                    <span>
                        TV
                    </span>
                </li>
                <li>
                    <span>
                        Games
                    </span>
                </li>
                <li>
                    <span>
                        Videos
                    </span>
                </li>
                <li>
                    <span>
                        News
                    </span>
                </li>
                <h6 id="link_section_title">
                    shop
                </h6>
                <li>
                    <span>
                        Shop DC
                    </span>
                </li>
                <li>
                    <span>
                        Shop DC Collectibles
                    </span>
                </li>
            </ul>
            <ul>
                <h6 id="link_section_title">
                    dc
                </h6>
                <li>
                    <span>
                        Terms of Use
                    </span>
                </li>
                <li>
                    <span>
                        Privacy policy (New)
                    </span>
                </li>
                <li>
                    <span>
                        Shop DC
                    </span>
                </li>
                <li>
                    <span>
                        Ad Choice
                    </span>
                </li>
                <li>
                    <span>
                        Advertising
                    </span>
                </li>
                <li>
                    <span>
                        Jobs
                    </span>
                </li>
                <li>
                    <span>
                        Subscriptions
                    </span>
                </li>
                <li>
                    <span>
                        Talent Workshops
                    </span>
                </li>
                <li>
                    <span>
                        CPSC Certificates
                    </span>
                </li>
                <li>
                    <span>
                        Ratings
                    </span>
                </li>
                <li>
                    <span>
                        Shop Help
                    </span>
                </li>
                <li>
                    <span>
                        Contact Us
                    </span>
                </li>
            </ul>
            <ul>
                <h6 id="link_section_title">
                    sites
                </h6>
                <li>
                    <span>
                        DC
                    </span>
                </li>
                <li>
                    <span>
                        MAD Magazine
                    </span>
                </li>
                <li>
                    <span>
                        DC Kids
                    </span>
                </li>
                <li>
                    <span>
                        DC Universe
                    </span>
                </li>
                <li>
                    <span>
                        DC Power Visa
                    </span>
                </li>
            </ul>
        </div>
        <div class="link_section_img">

        </div>
    </div>
</template>

<script>
export default {
    name: 'LinksSection',
    props: {

    }
}
</script>

<style lang="scss" scoped>
    .links_section{
        height: 500px;
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        align-items: center;
        padding: 0 10%;
        .link_section_items{
            height: 90%;
            width: 50%;
            // background-color: red;
            display: flex;
            justify-content: flex-start;
            ul{
                list-style: none;
                // border: 1px solid black;
                width: 25%;
                text-align: left;
                margin: 0;
                padding: 10px 5px;
                #link_section_title{
                    color: white;
                    text-transform: uppercase;
                    font-size: 16px;
                    padding-top: 10px;
                    padding-bottom: 10px;
                }
                li{
                    color: white;
                    font-size: 12px;
                    padding-top: 5px;
                    padding-bottom: 5px;
                    opacity: 0.8;
                    span{
                        margin-top: 10px;

                    }
                }
            }
        }
        .link_section_img{
            height: 100%;
            width: 50%;
            background-image: url('../assets/img/dc-logo-bg.png');
            background-size: cover;
            background-position: center;
            img {
                height: 80%;
                width: 80%;
            }
        }
    }
</style>