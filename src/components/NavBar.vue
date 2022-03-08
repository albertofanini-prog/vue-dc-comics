<template>
    <div class="navbar_container">
        <div class="navbar_logo">
            <img src="../assets/img/dc-logo.png" alt="dc-logo" id="dc-logo">
        </div>
        <div class="navbar_items">
            <ul class="navbar_items_list">
                <li class="navbar_item">
                    characters
                </li>
                <li class="navbar_item active">
                    comics
                </li>
                <li class="navbar_item">
                    movies
                </li>
                <li class="navbar_item">
                    tv
                </li>
                <li class="navbar_item">
                    games
                </li>
                <li class="navbar_item">
                    collectibles
                </li>
                <li class="navbar_item">
                    videos
                </li>
                <li class="navbar_item">
                    fans
                </li>
                <li class="navbar_item">
                    news
                </li>
                <li class="navbar_item">
                    shop
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
  }
}
</script>

<style scoped lang="scss">
    .navbar_container{
        // border: 3px solid green;
        height: 100px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 0px 10%;
    }
    .navbar_container > *{
        // border: 2px solid red;
        height: 100%;
        display: flex;
        align-items: center;
    }
    .navbar_logo{
        width: 30%;
        display: flex;
    }
    #dc-logo{
        align-self: left;
        margin: 10px;
        height: 95%;
    }
    .navbar_items{
        width: 70%;
    }
    .navbar_items_list{
        list-style: none;
        display: flex;
        align-items: baseline;
        gap: 25px;
        text-transform: uppercase;
        font-weight: 700;
        height: 100%;                                                                                    
    }
    .active{
        border-bottom: 5px solid #0D7DEC;
        color: #0D7DEC;
    }
    .navbar_item{
        height: 100%;
        display: flex;
        align-items: center;
    }
</style>