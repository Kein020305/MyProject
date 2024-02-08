<template>
    <div class="block_menu">
        <div class="header_left">
            <div class="logo">RosyGlow</div>
            <div>
                <ul class="ul_menu">
                    <li><a href="#">Каталог</a></li>
                    <li><a href="#">Акции</a></li>
                    <li><a href="#">Доставка и оплата</a></li>
                    <li><a href="#">О компании</a></li>
                    <li><a href="#">Контакты</a></li>
                </ul>
            </div>
        </div>
        <div>
            <ul class="ul_menu">
                <li><a href="#"><img src="../assets/menu/search.png"></a></li>
                <li><a href="#"><img src="../assets/menu/like.png"></a></li>
                <li><a href="#"><img src="../assets/menu/profile.png"></a></li>
                <li><a href="#"><img src="../assets/menu/shoppingcart.png"></a></li>
            </ul>
        </div>
    </div>
</template>
<style>
.block_menu{
    width: 100%;
    display: flex;
    justify-content: space-around;
    background-color: snow;
}
.header_left{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
}
.logo{
    font-family: 'Bradley Hand', cursive;
    font-size: 45px;
    color: indigo;
}
a{
    color: black;
    text-decoration: none;
}
ul{
    list-style-type: none;
}
.ul_menu{
    display: flex;
    flex-direction: row;
    font-size: 15px;
}
li{
    margin-right: 1.5em;
}
</style>
