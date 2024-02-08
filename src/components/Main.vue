<template>
    <main>
        <MainCarousel></MainCarousel>
        <div class="block_main">
            <div class="info">
                <h2>Акции</h2>
                <div class="promotion">
                    <a href="#"><img src="../assets/promotion/promotion1.jpg" style="height: 400px; margin-right: 30px;"></a>
                    <a href="#"><img src="../assets/promotion/promotion2.jpg" style="height: 400px;"></a>
                </div>
            </div>
            <div class="info">
                <h2>Популярное</h2>
                <div class="items">
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/tush.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Vivienne Sabo Тушь для ресниц Cabaret</div>
                                <div class="price">369 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/penka.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Manyo Factory пенка для умывания Pure Deep Cleansing Foam</div>
                                <div class="price">1 490 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products//shampun1.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">OLLIN Professional шампунь Beauty family</div>
                                <div class="price">430 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/pumyana.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Relouis румяна Pro blush duo</div>
                                <div class="price">241 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/parfym1.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Lanvin парфюмерная вода Marry Me!</div>
                                <div class="price">2 635 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/pomada.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">LUXVISAGE помада для губ перламутровая с глянцевым блеском</div>
                                <div class="price">232 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/teni1.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">REVOLUTION Палетка теней Forever flawless</div>
                                <div class="price">991 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/cream.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Institut Esthederm крем Photo Regul pigmentation irregularities</div>
                                <div class="price">4 996 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/parfym2.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Lanvin парфюмерная вода Eclat d'Arpege pour Femme</div>
                                <div class="price">2 480 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/tint.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Inglot тинт для губ HD Lip Tint Matte</div>
                                <div class="price">1 610 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/parfym3.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">Vilhelm Parfumerie парфюмерная вода Smoke Show</div>
                                <div class="price">2 250 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                    <div class="item">
                        <a href="#" class="a_item">
                            <div><img src="../assets/products/shampun2.webp" class="product"></div>
                            <div class="item_content">
                                <div class="name">La'dor шампунь для волос Moisture Balancing</div>
                                <div class="price">810 руб.</div>
                                <div class="btn_detail">Подробнее</div>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>
<script>
import MainCarousel from '@/components/MainCarousel.vue'

export default {
    components: {
      MainCarousel
    }
  }
</script>

<style>
.block_main{
    margin-top: 40px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
}
h2{
    margin-bottom: 30px;
    font-weight: normal;
}
.info{
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 40px;
}
.promotion{
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
}
.items{
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-start;
}
.item{
    width: 20%;
    margin-bottom: 30px;
}
.a_item{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.product{
    height: 12rem;
}
.item_content{
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 14px;
    text-align: center;
}
.name{
    width: 15rem;
    height: 50px;
    margin: 10px 0;
}
.price{
    margin: 10px 0;
}
.btn_detail{
    border: 1px solid skyblue;
    width: 8rem;
}
</style>