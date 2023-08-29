<template>
  <div>
    <VueSlickCarousel v-bind="slickOptions">
      <div>
        <div class="slider__block">
          <div class="slider__block__col">
            <div class="slider__block__small">
              <img src="../assets/img/img-small-1.webp" alt="" />
              <div class="slider__block__small__menu">
                <div class="slider__block__small__menu__container">
                  <div class="slider__block__big__menu__text">
                    <h3>Скандинавская деревня</h3>
                    <p>4 экскурсии</p>
                  </div>
                  <div class="slider__block__small__menu__btn">
                    <div class="btn-slider">
                      <p>Подробнее</p>
                      <img src="../assets/img/arrow-small.svg" alt="" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="slider__block__small">
              <img src="../assets/img/img-small-2.webp" alt="" />
              <div class="slider__block__small__menu">
                <div class="slider__block__small__menu__container">
                  <div class="slider__block__big__menu__text">
                    <h3>Скандинавская деревня</h3>
                    <p>4 экскурсии</p>
                  </div>
                  <div class="slider__block__small__menu__btn">
                    <div class="btn-slider">
                      <p>Подробнее</p>
                      <img src="../assets/img/arrow-small.svg" alt="" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="slider__block__big">
            <img src="../assets/img/img-big.webp" alt="" />
            <div class="slider__block__big__menu">
              <div class="slider__block__big__menu__container">
                <div class="slider__block__big__menu__text">
                  <h3>Скандинавская деревня</h3>
                  <p>4 экскурсии</p>
                </div>
                <div class="btn-slider">
                  <p>Подробнее</p>
                  <img src="../assets/img/arrow-small.svg" alt="" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="slider__block">
          <div class="slider__block__col">
            <div class="slider__block__small">
              <img src="../assets/img/img-small-3.webp" alt="" />
              <div class="slider__block__small__menu">
                <div class="slider__block__small__menu__container">
                  <div class="slider__block__big__menu__text">
                    <h3>Скандинавская деревня</h3>
                    <p>4 экскурсии</p>
                  </div>
                  <div class="slider__block__small__menu__btn">
                    <div class="btn-slider">
                      <p>Подробнее</p>
                      <img src="../assets/img/arrow-small.svg" alt="" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="slider__block__small">
              <img src="../assets/img/img-small-4.webp" alt="" />
              <div class="slider__block__small__menu">
                <div class="slider__block__small__menu__container">
                  <div class="slider__block__big__menu__text">
                    <h3>Скандинавская деревня</h3>
                    <p>4 экскурсии</p>
                  </div>
                  <div class="slider__block__small__menu__btn">
                    <div class="btn-slider">
                      <p>Подробнее</p>
                      <img src="../assets/img/arrow-small.svg" alt="" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="slider__block__big">
            <img src="../assets/img/img-big.webp" alt="" />
            <div class="slider__block__big__menu">
              <div class="slider__block__big__menu__container">
                <div class="slider__block__big__menu__text">
                  <h3>Скандинавская деревня</h3>
                  <p>4 экскурсии</p>
                </div>
                <div class="btn-slider">
                  <p>Подробнее</p>
                  <img src="../assets/img/arrow-small.svg" alt="" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="slider__block">
          <div class="slider__block__col">
            <div class="slider__block__small">
              <img src="../assets/img/img-small-1.webp" alt="" />
              <div class="slider__block__small__menu">
                <div class="slider__block__small__menu__container">
                  <div class="slider__block__big__menu__text">
                    <h3>Скандинавская деревня</h3>
                    <p>4 экскурсии</p>
                  </div>
                  <div class="slider__block__small__menu__btn">
                    <div class="btn-slider">
                      <p>Подробнее</p>
                      <img src="../assets/img/arrow-small.svg" alt="" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="slider__block__small">
              <img src="../assets/img/img-small-2.webp" alt="" />
              <div class="slider__block__small__menu">
                <div class="slider__block__small__menu__container">
                  <div class="slider__block__big__menu__text">
                    <h3>Скандинавская деревня</h3>
                    <p>4 экскурсии</p>
                  </div>
                  <div class="slider__block__small__menu__btn">
                    <div class="btn-slider">
                      <p>Подробнее</p>
                      <img src="../assets/img/arrow-small.svg" alt="" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="slider__block__big">
            <img src="../assets/img/img-big.webp" alt="" />
            <div class="slider__block__big__menu">
              <div class="slider__block__big__menu__container">
                <div class="slider__block__big__menu__text">
                  <h3>Скандинавская деревня</h3>
                  <p>4 экскурсии</p>
                </div>
                <div class="btn-slider">
                  <p>Подробнее</p>
                  <img src="../assets/img/arrow-small.svg" alt="" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </VueSlickCarousel>
  </div>
</template>
 
<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  components: { VueSlickCarousel },
  data() {
    return {
      slickOptions: {
        /*
        arrows: false,
        dots: true,
        */
        infinite: true,
        centerMode: true,
        slidesToShow: 1,
        slidesToScroll: 1,
        variableWidth: true,
        /*
        autoplay: true,
        autoplaySpeed: 2000,
        */
      },
    };
  },
};
</script> 