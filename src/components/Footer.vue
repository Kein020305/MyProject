<!--Footer.vue-->
<template>
<footer>
    <div class="inner">
            <div class="fmenu">
                <div class="logo" style="font-size: 30px;">RosyGlow</div>
                <div>@RosyGlow</div>
                <a href="#">Политика конфидециальности</a>
                <a href="#">Согласие на обработку персональных данных</a>
                <div class="address">Используя данный сайт, вы автоматически принимаете условия
                    пользовательского соглашения и соглашаетесь с политикой конфиденциальности.</div>
            </div>
            <div class="fmenu">
                <div class="subtitle">О магазине</div>
                <ul class="ul_footer">
                    <li><a href="#">Главная</a></li>
                    <li><a href="#">Акции</a></li>
                    <li><a href="#">Доставка и оплата</a></li>
                    <li><a href="#">О компании</a></li>
                    <li><a href="#">Новости</a></li>
                    <li><a href="#">Статьи</a></li>
                </ul>
            </div>
            <div class="fmenu">
                <div class="subtitle">Каталог</div>
                <ul class="ul_footer">
                    <li><a href="#">Уход после косметики</a></li>
                    <li><a href="#">Уход за кожей</a></li>
                    <li><a href="#">Личная гигиена</a></li>
                    <li><a href="#">Макияж</a></li>
                    <li><a href="#">Парфюмерия</a></li>
                    <li><a href="#">Уход за волосами</a></li>
                </ul>
            </div>
            <div class="fmenu">
                <div class="subtitle">Свяжитесь с нами</div>
                <div class="address">123456, г.Санкт-Петербург, ТЦ Цветочек, пр.Ударников, 1</div>
                <div>
                    <span class="mail">E-mail:
                        <a href="#">cosmetic@mail.ru</a>
                    </span>
                </div>
                <a href="#" class="phone">8-960-333-22-11</a>
                <div>
                    <a href="#"><img class="social" src="../assets/socials/VK_black.png"></a>
                    <a href="#"><img class="social" src="../assets/socials/Ok_black.png"></a>
                    <a href="#"><img class="social" src="../assets/socials/Facebook_black.png"></a>
                    <a href="#"><img class="social" src="../assets/socials/YouTube_black.png"></a>
                    <a href="#"><img class="social" src="../assets/socials/Telegram_black.png"></a>
                </div>
            </div>
        </div>
</footer>
</template>
<style>
footer{
    width: 100%;
    background-color: snow;
    font-size: 14px;
    padding: 50px 0;
}
.inner {
    margin: 0 auto;
    display: flex;
    justify-content: space-around;
}
.fmenu{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    line-height: 2;
}
.subtitle{
    font-size: 16px;
    margin-bottom: 15px;
}
.address{
    width: 350px;
    line-height: 1.5;
}
.ul_footer {
    padding: 0;
    margin: 0;
}
.social{
    width: 1.7em;
    margin: 10px 0.5em 0 0;
}
</style>