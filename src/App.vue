<template>
  <div class="wrapper-main">
    <Loader :loading="loading" />
    <div>
      <div class="wrapper-header my-4 row">
        <div
          class="left-content d-flex justify-content-between align-items-center my-2 col-sm-12 col-md-5 col-xl-4"
        >
          <div class="logo-item d-flex cursor-pointer">
            <div class="logo-icon">
              <img src="../assets/images/logo.svg" alt="" />
            </div>
            <div
              class="logo-title d-flex justify-content-center align-items-center"
            >
              <h2 class="logo-title-left">Hotline</h2>
              <h2 class="logo-title-right ms-1">Gaming</h2>
            </div>
          </div>
        </div>
        <div class="empty-wrapper col-sm-12 col-md-1 col-xl-4"></div>
        <div
          class="right-content d-flex justify-content-end align-items-center col-sm-12 col-md-6 col-xl-4"
        >
          <a
            href="https://vk.com/hotlinegaming"
            class="vk-icon d-flex justify-content-center align-items-center cursor-pointer me-3 my-2"
          >
            <svg
              width="48"
              height="48"
              viewBox="0 0 48 48"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M24 4C13 4 4 13 4 24C4 35 13 44 24 44C35 44 44 35 44 24C44 13 35 4 24 4Z"
                fill="#1976D2"
              />
              <path
                d="M25.2 33.2C16.2 33.2 11.1 27.1 10.9 16.8H15.4C15.5 24.3 18.9 27.5 21.5 28.1V16.8H25.7V23.3C28.3 23 31 20.1 31.9 16.8H36.1C35.4 20.8 32.4 23.8 30.3 25C32.4 26 35.8 28.6 37 33.2H32.3C31.3 30.1 28.8 27.7 25.5 27.3V33.2H25.2Z"
                fill="white"
              />
            </svg>
          </a>
          <div class="numper-wrapper card-c d-flex cursor-pointer">
            <div class="icon-call-phone">
              <svg
                width="30"
                height="30"
                viewBox="0 0 30 30"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M19.4452 18.1846L18.8759 18.784C18.8759 18.784 17.5226 20.2087 13.8289 16.3199C10.1351 12.431 11.4884 11.0063 11.4884 11.0063L11.8469 10.6289C12.7301 9.69905 12.8134 8.20621 12.0428 7.11637L10.4666 4.88701C9.51285 3.53813 7.66995 3.35994 6.57681 4.5108L4.61481 6.57642C4.07279 7.14707 3.70956 7.88681 3.75361 8.70742C3.8663 10.8068 4.76339 15.3237 9.7692 20.594C15.0776 26.1827 20.0585 26.4049 22.0954 26.2039C22.7396 26.1402 23.2999 25.7929 23.7514 25.3175L25.5271 23.448C26.7257 22.1861 26.3877 20.0227 24.8541 19.14L22.466 17.7654C21.459 17.1857 20.2322 17.356 19.4452 18.1846Z"
                  fill="#F1F1F1"
                />
              </svg>
            </div>
            <div class="number">
              <h4>+7 928 207-76-66</h4>
            </div>
          </div>
        </div>
      </div>
      <div class="wrapper-welcome card-c p-5">
        <div class="welcome-title">
          <h3 class="d-flex">
            <p class="color-pink me-2"><b> Добро пожаловать! </b></p>
          </h3>
        </div>
        <div class="welcome-subtitle">
          <h3 class="space">
            В компьютерный клуб <br />
            “Hotline Gaming”
          </h3>
        </div>
        <div class="adress-wrapper mt-5 bold">
          Адрес: Геленджик, ул.Ленина 14, центр города
        </div>
      </div>
      <div class="wrapper-services my-5 card-c">
        <div class="row mb-5">
          <div class="container-right col-12 col-md-12 col-xl-6">
            <div class="services-title mb-4 pb-4">
              <h2 class="space bold">Наши услуги</h2>
            </div>
            <h3>VIP (6pc)</h3>
            <div class="price-wrapper my-5">
              <img src="./assets/images/services.png" alt="" />
              <div
                class="hour-price d-flex flex-column justify-content-center align-items-center"
              >
                <div class="hour-price-item d-flex my-3">
                  <div class="hour-price-item-num bold pe-3">1 час</div>
                  <div class="hour-price-item-price bold ps-3">100 р</div>
                </div>
                <div class="hour-price-item d-flex my-3">
                  <div class="hour-price-item-num bold pe-3">3 час</div>
                  <div class="hour-price-item-price bold ps-3">350 р</div>
                </div>
                <div class="hour-price-item d-flex my-3">
                  <div class="hour-price-item-num bold pe-3">5 час</div>
                  <div class="hour-price-item-price bold ps-3">550 р</div>
                </div>
              </div>
            </div>
          </div>
          <div class="container-left col-12 col-md-12 col-xl-6 pe-4">
            <div class="price-title">
              <h3 class="bold ms-4">Акции</h3>
            </div>
            <div class="card-e d-flex my-4">
              <div
                class="card-title d-flex justify-content-center align-items-center pe-4"
              >
                Пакет “Утро”
              </div>
              <div
                class="card-price d-flex justify-content-center align-items-center ps-5"
              >
                30% скидка на все <br />
                утренние часы
              </div>
            </div>
            <div class="card-e d-flex my-4">
              <div
                class="card-title d-flex justify-content-center align-items-center pe-4"
              >
                Пакет “Утро”
              </div>
              <div
                class="card-price d-flex justify-content-center align-items-center ps-5"
              >
                30% скидка на все <br />
                утренние часы
              </div>
            </div>
          </div>
        </div>
        <div class="row mb-5">
          <div
            v-for="(item, index) in items"
            :key="index"
            class="accordion-item col-12 col-md-6 col-xl-6"
          >
            <div
              :class="[
                'accordion-header mt-4 ps-5 d-flex align-items-center justify-content-between',
                { 'active-item': isActive(index) },
              ]"
              @click="toggle(index)"
            >
              <h4 class=" my-4">
                {{ item.title }}
              </h4>
              <span :class="['arrow me-4', { 'rotate': isActive(index) }]">▼</span>
            </div>
            <transition name="accordion">
              <div v-show="isActive(index)" class="accordion-content">
                <div
                  class="d-flex flex-column justify-content-center align-items-center w-100 h-100"
                >
                  <div class="item d-flex my-4">
                    <div class="left-item px-3">
                      {{ item.one }}
                    </div>
                    <div class="right-item px-3">
                      <b>
                        {{ item.priceone }}
                      </b>
                    </div>
                  </div>
                  <div class="item d-flex my-4">
                    <div class="left-item px-3">
                      {{ item.two }}
                    </div>
                    <div class="right-item px-3">
                      <b>
                        {{ item.pricetwo }}
                      </b>
                    </div>
                  </div>
                  <div class="item d-flex my-4">
                    <div class="left-item px-3">
                      {{ item.three }}
                    </div>
                    <div class="right-item px-3">
                      <b>
                        {{ item.pricethree }}
                      </b>
                    </div>
                  </div>
                </div>
              </div>
            </transition>
          </div>
        </div>
        <div class="alert-wrapper">
          <p class="color-pink">Примечание:</p>
          <p>
            За более подробной информации можете обратиться по номеру телефона
            или в нашей группе в “ВК”
          </p>
        </div>
      </div>
      <div class="alert-wrapper-phone card-c">
        <p class="color-pink">Примечание:</p>
        <p>
          За более подробной информации можете обратиться по номеру телефона или
          в нашей группе в “ВК”
        </p>
      </div>
      <div class="wrapper-about card-c p-4">
        <div class="row">
          <div class="col-12 col-md-6 col-xl-8">
            <div class="card-b">
              <div class="slider-title mb-5">
                <h2 class="d-flex mb-3">
                  <h2 class="underline me-2">Что там</h2>
                  <h2 class="color-pink">внутри</h2>
                </h2>
              </div>
              <swiper
                :modules="modules"
                :slides-per-view="slidesPerView"
                :space-between="50"
                :scrollbar="{ draggable: true }"
                @swiper="onSwiper"
                @slideChange="onSlideChange"
                :breakpoints="breakpoints"
              >
                <swiper-slide
                  class="d-flex justify-content-center aling-items-center"
                >
                  <img
                    class="swiper-item"
                    src="./assets/images/rooms1.png"
                    alt=""
                    @click="showModal = true"
                  />
                  <div
                    v-if="showModal"
                    class="modal"
                    @click="showModal = false"
                  >
                    <img
                      src="./assets/images/rooms1.png"
                      alt="Full Size"
                      class="full-size-image"
                      @click.stop
                    />
                  </div>
                </swiper-slide>
                <swiper-slide
                  class="d-flex justify-content-center aling-items-center"
                >
                  <img
                    class="swiper-item"
                    src="./assets/images/image1.jpg"
                    alt=""
                  />
                </swiper-slide>
                <swiper-slide
                  class="d-flex justify-content-center aling-items-center"
                >
                  <img
                    class="swiper-item"
                    src="./assets/images/image2.jpg"
                    alt=""
                  />
                </swiper-slide>
                <swiper-slide
                  class="d-flex justify-content-center aling-items-center"
                >
                  <img
                    class="swiper-item"
                    src="./assets/images/image3.jpg"
                    alt=""
                  />
                </swiper-slide>
                <swiper-slide
                  class="d-flex justify-content-center aling-items-center"
                >
                  <img
                    class="swiper-item"
                    src="./assets/images/image4.jpg"
                    alt=""
                  />
                </swiper-slide>
                <swiper-slide
                  class="d-flex justify-content-center aling-items-center"
                >
                  <img
                    class="swiper-item"
                    src="./assets/images/image5.jpg"
                    alt=""
                  />
                </swiper-slide>
              </swiper>
            </div>
          </div>
          <div class="col-12 col-md-6 col-xl-4 h-100 mt-4">
            <div class="card-b">
              <h3 class="title-sub mb-4">Описание</h3>
              <p>Первый компьютерный клуб с домашней атмосферой</p>
              <p>
                Наши мощные игровые компьютеры позволят Вам комфортно играть в
                самые требовательные игры, а атмосфера не оставит вас
                равнодушными
              </p>
              <div
                class="card-c d-flex justify-content-center align-items-center fire-wrapper cursor-pointer"
              >
                <div class="operting-mode me-2">Работаем круглосуточно!</div>
                <div class="icon-fire" v-html="svgFire"></div>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-12 col-xl-12 mt-5">
            <div class="row">
              <div class="col-12 col-md-6 col-xl-4 mt-4">
                <div class="card-e about-item">
                  <div class="icon-about">
                    <img src="../assets/images/about-one.png" alt="" />
                  </div>
                  <div class="title-about">
                    <h2>Цена - качество</h2>
                  </div>
                  <div class="subtitle-about">
                    Наш компьютерный клуб отличается лучшим сочетанием цены и
                    качества на рынке. Мы предлагаем высокие стандарты
                    обслуживания, современное оборудование, комфортные условия и
                    доступные цены для всех наших клиентов.
                  </div>
                </div>
              </div>
              <div class="col-12 col-md-6 col-xl-4 mt-4">
                <div class="card-e about-item">
                  <div class="icon-about">
                    <img src="../assets/images/about-two.png" alt="" />
                  </div>
                  <div class="title-about">
                    <h2>Местоположение</h2>
                  </div>
                  <div class="subtitle-about">
                    Клуб удобно расположен в самом центре города, что делает нас
                    идеальным местом для проведения времени в любое время суток.
                  </div>
                </div>
              </div>
              <div class="col-12 col-md-6 col-xl-4 mt-4">
                <div class="card-e about-item">
                  <div class="icon-about">
                    <img src="../assets/images/about-three.png" alt="" />
                  </div>
                  <div class="title-about">
                    <h2>Атмосфера</h2>
                  </div>
                  <div class="subtitle-about">
                    Мы заботимся о вашем комфорте и удовлетворении, поэтому мы
                    оснастили наш клуб современными и качественными
                    компьютерами, мониторами и периферийными устройствами.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="wrapper-map card-c p-4 my-5 pe-5">
        <div class="row">
          <div class="col-12 col-md-5 col-xl-4 d-flex justify-content-center">
            <div>
              <div class="title-map">
                <h2>Наш адрес:</h2>
                <p>Адрес: Геленджик, ул.Ленина 14, центр города</p>
              </div>
              <p>
                Независимо от ваших целей - работа, учеба или отдых - наше
                уютное пространство открыто для вас. Мы стремимся создать
                атмосферу дружелюбия и удовольствия, где каждый посетитель
                чувствует себя как дома.
              </p>
            </div>
          </div>
          <div class="col-1 col-md-1 col-xl-2"></div>
          <div class="col-12 col-md-6 col-xl-6">
            <div class="w-100">
              <div class="wrapper-yandex-map ms-3">
                <div id="map">
                  <iframe
                    src="https://yandex.ru/map-widget/v1/?um=constructor%3A07c9bfb252a94bd4ff548cc0c3d844a78572f4b4a75e5f6d2465c4b6cc5f3860&amp;source=constructor"
                    height="400"
                    class="map"
                    frameborder="0"
                  >
                  </iframe>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-wrapper d-flex flex justify-content-end">
        <p class="footer-text">© areaWD</p>
      </div>
    </div>
  </div>
</template>

<script>
import Loader from "@/components/Loader.vue";

import "./assets/bootstrap.scss";

// импорт библиотеки swiper
import { Swiper, SwiperSlide } from "swiper/vue";

// импорт элементов библиотеки swiper, для создания компоненты слайдера
import { Navigation, Pagination, Scrollbar, A11y } from "swiper/modules";

// импорт стилей для элементов swiper
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";
import "swiper/css/scrollbar";

export default {
  name: "AreaWD-project",
  // публикация переменных для какой-либо логики
  data() {
    return {
      fio: "",
      rank: "",
      telegram: "",
      email: "",
      dateRegister: "",
      loading: true,
      svgFire: `
        <svg width="30" height="40" viewBox="0 0 30 40" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g clip-path="url(#clip0_4_175)">
        <path d="M30 25.7625C30 33.625 23.2812 40 15 40C6.71875 40 0 33.625 0 25.7625C0 17.3688 9.8625 4.71253 13.5938 0.23128C13.6725 0.122141 13.7843 0.0413272 13.9127 0.00085666C14.041 -0.0396139 14.179 -0.0375794 14.3061 0.00665735C14.4332 0.0508941 14.5426 0.13497 14.6181 0.246383C14.6936 0.357796 14.7311 0.490595 14.725 0.62503C14.4062 4.37503 14.625 12.4 21.3375 16.4C21.4718 16.491 21.6362 16.5263 21.796 16.4983C21.9558 16.4703 22.0984 16.3813 22.1937 16.25C23.0351 15.0106 23.5214 13.5647 23.6 12.0688C23.6073 11.9314 23.6598 11.8003 23.7492 11.6957C23.8387 11.5912 23.9601 11.5191 24.0947 11.4906C24.2293 11.4621 24.3696 11.4788 24.4937 11.5381C24.6178 11.5975 24.7189 11.6961 24.7812 11.8188C27.6375 16.5188 30 21.65 30 25.7625Z" fill="#FF7F00"/>
        <path d="M5.625 31.1C5.625 36.0187 9.825 40 15 40C20.175 40 24.375 36.0187 24.375 31.1C24.375 26.1812 18.9438 18.9062 16.35 15.7187C16.2723 15.6066 16.1601 15.5231 16.0304 15.4807C15.9007 15.4384 15.7608 15.4396 15.6319 15.4842C15.503 15.5288 15.3923 15.6144 15.3166 15.7278C15.2408 15.8412 15.2043 15.9763 15.2125 16.1125C15.3063 18.6125 14.8687 22.8437 11.2437 25.1437C11.1733 25.1904 11.0942 25.2222 11.0111 25.2374C10.928 25.2526 10.8427 25.2508 10.7604 25.2321C10.678 25.2134 10.6003 25.1782 10.5319 25.1287C10.4635 25.0791 10.4059 25.0162 10.3625 24.9437C10.0474 24.4042 9.83551 23.8108 9.7375 23.1937C9.72324 23.0579 9.6649 22.9305 9.5714 22.831C9.47789 22.7315 9.35437 22.6654 9.21972 22.6427C9.08506 22.62 8.94669 22.642 8.82575 22.7054C8.70481 22.7688 8.60795 22.8701 8.55 22.9937C6.90625 25.7625 5.625 28.7062 5.625 31.1Z" fill="#FFDA00"/>
        <path d="M20.1562 35.1063C20.1425 35.7673 19.9979 36.419 19.7306 37.0237C19.4634 37.6284 19.0789 38.1741 18.5993 38.6292C18.1198 39.0843 17.5548 39.4398 16.937 39.6751C16.3191 39.9104 15.6608 40.0209 15 40.0001C14.3392 40.0209 13.6809 39.9104 13.063 39.6751C12.4452 39.4398 11.8802 39.0843 11.4007 38.6292C10.9211 38.1741 10.5366 37.6284 10.2694 37.0237C10.0021 36.419 9.85747 35.7673 9.84375 35.1063C9.84375 32.6876 12.2188 29.2501 13.75 27.2876C13.8248 27.1801 13.9313 27.0989 14.0547 27.0553C14.1781 27.0116 14.3121 27.0079 14.4378 27.0445C14.5634 27.0811 14.6744 27.1562 14.7551 27.2592C14.8358 27.3623 14.8821 27.488 14.8875 27.6188C14.8899 28.3801 15.059 29.1315 15.3829 29.8204C15.7069 30.5093 16.1778 31.1189 16.7625 31.6063C16.8389 31.6721 16.9301 31.7184 17.0283 31.7413C17.1264 31.7642 17.2287 31.763 17.3263 31.7379C17.424 31.7127 17.514 31.6643 17.5889 31.5968C17.6638 31.5292 17.7212 31.4446 17.7562 31.3501C17.7936 31.2323 17.8649 31.1283 17.9613 31.0511C18.0577 30.9739 18.1748 30.927 18.2979 30.9163C18.4209 30.9056 18.5444 30.9316 18.6526 30.991C18.7609 31.0504 18.8492 31.1405 18.9062 31.2501C19.6176 32.4206 20.0456 33.7411 20.1562 35.1063Z" fill="white"/>
        </g>
        <defs>
        <clipPath id="clip0_4_175">
        <rect width="30" height="40" fill="white"/>
        </clipPath>
        </defs>
        </svg>

        `,
      items: [
        {
          title: "VIP (6pc)",
          one: "1 час",
          priceone: "100 р",
          two: "3 час",
          pricetwo: "350 р",
          three: "5 час",
          pricethree: "550 р",
        },
        {
          title: "VIP (2pc и Xbox)",
          one: "1 час",
          priceone: "250 р",
          two: "3 час",
          pricetwo: "600 р",
          three: "5 час",
          pricethree: "900 р",
        },
        {
          title: "Mini VIP",
          one: "1 час",
          priceone: "200 р",
          two: "3 час",
          pricetwo: "500 р",
          three: "5 час",
          pricethree: "700 р",
        },
        {
          title: "Телевизор с PS4 pro",
          one: "1 час",
          priceone: "150 р",
          two: "3 час",
          pricetwo: "350 р",
          three: "5 час",
          pricethree: "500 р",
        },
      ],
      activeIndex: null,
    };
  },
  // выше мы импортировали компоненты.В функции components мы говорим о том, что это именно компонент, а не элемент или функция какой либо библиотеки либо фреймворка
  components: {
    Loader,
    Swiper,
    SwiperSlide,
  },
  methods: {
    toggle(index) {
      this.activeIndex = this.activeIndex === index ? null : index;
    },
    isActive(index) {
      return this.activeIndex === index;
    },
  },
  // это синтаксис option для библиотеки swiper, для более подробной документации https://swiperjs.com/
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log("slide change");
    };

    const breakpoints = {
      // если окно будет меньше 640px, будет виден только один элемент слайдера
      640: {
        slidesPerView: 1,
      },
      // если окно будет меньше 1200px, будет видно только два элемента слайдера
      1200: {
        slidesPerView: 2,
      },
      // если окно будет меньше 1300px, будет видно три элемента слайдера
      1300: {
        slidesPerView: 3,
      },
      //по умолчанию стоит 3 элемента слайдера
    };
    //возврат элементов и модулей, так как мы находимся внутри функции setup
    return {
      onSwiper,
      onSlideChange,
      modules: [Navigation, Pagination, Scrollbar, A11y],
      breakpoints,
    };
  },
};
</script>

<style scoped>
/*стандартные css стили*/

header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

.accordion-item {
  margin-bottom: 5px;
}
.accordion-header {
  background: var(--color-back);
  border-radius: 30px;
  cursor: pointer;
  padding: 10px;
}

.accordion-content {
  padding: 10px;
  background: var(--color-back);
}

.accordion-content {
  border-radius: 0 0 30px 30px;
}

.active-item {
  border-radius: 30px 30px 0 0;
}

.left-item {
  border-right: var(--color-white) solid 2px;
}

.arrow {
  transition: transform 0.3s ease;
}

.rotate {
  transform: rotate(90deg);
}



@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
