<template>
    <div class="main1">
        <div class="container">
          <div style="width: 100%; display: flex; justify-content: center;"><h2>Новинки</h2></div>
            <Carousel :itemsToShow="3.95" :wrapAround="true" :transition="500">
                <Slide :key="1">
                <div class="carousel__item">
                    <div class="slideee">
                        <div class="carousel-img-div">
                        </div>
                        
                        <div class="slide-text">
                          <div class="name">Limoni Тени для век Eye-Shadow</div>
                          <div class="price-buy">
                            <p class="price-price">332 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <Slide :key="2">
                <div class="carousel__item">
                    <div class="slideee">
                        <div class="carousel-img-div2">

                        </div>
                        <div class="slide-text">
                          <div class="name">L'Oreal Paris, Тональный крем ALLIANCE PERFECT СОВЕРШЕННОЕ СЛИЯНИЕ</div>
                          <div class="price-buy">
                            <p class="price-price">758 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <Slide :key="3">
                <div class="carousel__item">
                    <div class="slideee">
                        <div class="carousel-img-div3">

                        </div>
                        <div class="slide-text">
                          <div class="name">TRESemme кондиционер Repair & Protect</div>
                          <div class="price-buy">
                            <p class="price-price">478 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <Slide :key="4">
                <div class="carousel__item">
                    <div class="slideee">
                        <div class="carousel-img-div4">

                        </div>
                        <div class="slide-text">
                          <div class="name">OZ! OrganicZone Сахарный скраб для тела Папайя</div>
                          <div class="price-buy">
                            <p class="price-price">382 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <Slide :key="5">
                <div class="carousel__item">
                    <div class="slideee">
                        <div class="carousel-img-div5">

                        </div>
                        <div class="slide-text">
                          <div class="name">Manyo Factory гидрофильное масло для снятия макияжа Pure Cleansing Oil</div>
                          <div class="price-buy">
                            <p class="price-price">1 950 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <Slide :key="6">
                <div class="carousel__item">
                  <div class="slideee">
                        <div class="carousel-img-div6">

                        </div>
                        <div class="slide-text">
                          <div class="name">Pupa Карандаш для губ True Lips</div>
                          <div class="price-buy">
                            <p class="price-price">461 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <Slide :key="7">
                <div class="carousel__item">
                  <div class="slideee">
                        <div class="carousel-img-div7">

                        </div>
                        <div class="slide-text">
                          <div class="name">Lanvin парфюмерная вода Jeanne Lanvin</div>
                          <div class="price-buy">
                            <p class="price-price">1 290 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <Slide :key="8">
                <div class="carousel__item">
                  <div class="slideee">
                        <div class="carousel-img-div8">

                        </div>
                        <div class="slide-text">
                          <div class="name">Гель для душа Camay Botanicals Гранат & коллаген</div>
                          <div class="price-buy">
                            <p class="price-price">250 руб.</p>
                            <div class="buy-button">Подробнее</div>
                          </div>
                        </div>
                    </div>
                </div>
                </Slide>
                <template #addons>
                <Navigation />
                <Pagination />
                </template>
                
            </Carousel>
        </div>
    </div>
</template>
<script>
import { Carousel, Slide, Navigation, Pagination } from 'vue3-carousel'
import 'vue3-carousel/dist/carousel.css'

export default {
  name: 'MyMain',
  components: {
    Carousel,
    Slide,
    Pagination,
    Navigation,
  },
}
</script>
<style scoped>
a {
    text-decoration: none;
}
h2{
    margin-bottom: 30px;
    font-weight: normal;

}
.main1 {
    margin-top: 100px;
    margin-bottom: 100px;
    width: 100%;
    display: flex;
    justify-content: center;
}
p {
    margin: 0;
}
.carousel-img {
    width: 337px;
    height: 300px;
    
}
.carousel-img-div {
    margin: 0px 20%;
    height: 60%;
    background-image: url("../assets/products/teni2.webp");
    background-size: cover;
    
}
.carousel-img-div2 {
    margin: 0px 15%;
    height: 60%;
    background-image: url("../assets/products/ton.webp");
    background-size: cover;
}
.carousel-img-div3 {
    margin: 0px 40%;
    height: 60%;
    background-image: url("../assets/products/konder.webp");
    background-size: cover;
}
.carousel-img-div4 {
    height: 60%;
    background-image: url("../assets/products/scrab.webp");
    background-size: cover;
}
.carousel-img-div5 {
    margin: 0px 40%;
    height: 60%;
    background-image: url("../assets/products/gidrof_maslo.webp");
    background-size: cover;
}
.carousel-img-div6 {
    margin: 0px 18%;
    height: 60%;
    background-image: url("../assets/products/karandash_gub.webp");
    background-size: cover;
}
.carousel-img-div7 {
    margin: 0px 30%;
    height: 60%;
    background-image: url("../assets/products/parfym4.webp");
    background-size: cover;
}
.carousel-img-div8 {
    margin: 0px 40%;
    height: 60%;
    background-image: url("../assets/products/gel.webp");
    background-size: cover;
}
.container {
    min-width: 1414px;
    max-width: 1414px;
    margin-left: 5px;
    margin-right: 5px;
}
.carousel__slide {
  padding: 5px;
}

.carousel__viewport {
  perspective: 2000px;
}

.carousel__track {
  transform-style: preserve-3d;
}

.carousel__slide--sliding {
  transition: 0.5s;
}

.carousel__slide {
  opacity: 0.9;
  transform: rotateY(-20deg) scale(0.8);
}

.carousel__slide--active ~ .carousel__slide {
  transform: rotateY(20deg) scale(0.8);
}

.carousel__slide--prev {
  opacity: 1;
  transform: rotateY(-10deg) scale(0.9);
}

.carousel__slide--next {
  opacity: 1;
  transform: rotateY(10deg) scale(0.9);
}

.carousel__slide--active {
  opacity: 1;
  transform: rotateY(0) scale(1);
}

.carousel__item {
  min-height: 400px;
  width: 100%;
  background-color: rgb(255, 255, 255);
  color: var(--vc-clr-white);
  font-size: 20px;
  display: flex;
  border: 1px solid rgba(0,0,0,0.5);
}
.slideee {
    width: inherit;
    height: inherit;
    display: flex;
    flex-direction: column;
    
}
.name {
  color: #000;
  height: 50px;
  font-family: 'Ubuntu', sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  margin-top: 20px;
  margin-bottom: 10px;
}
.carousel__slide {
  padding: 10px;
}
.slide-text {
  text-align: left;
  display: flex;
  flex-direction: column;
  margin-left: 20px;
}
.price-buy {
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
}
.price-price {
  color: #000;
  font-size: 20px;
  font-style: normal;
  line-height: normal;
  margin-right: 20px;
  margin-bottom: 3px;
}
.buy-button {
  
  width: 125px;
  background-size: 300% 100%;

  color: #000;
  display: flex;
  border-radius: 14px;
  justify-content: center;
  align-items: center;
  height: 55px;
  cursor: pointer;
  margin-right: 20px;
  border: 1px solid skyblue;
}
.buy-button:focus {
    outline: none;
}
.carousel__prev,
.carousel__next {
  box-sizing: content-box;
  border: 5px solid white;
  
}
</style>