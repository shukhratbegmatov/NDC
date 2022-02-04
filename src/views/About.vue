<template>
  <div class="bg_main">
    <div class="container">
      <Navbar></Navbar>
      <section class="s_section">
        <div class="f_main_text">
          <div>
            <h3>Мы cоздаем продукт, помогающий
              развивать бизнес</h3>
          </div>
        </div>
        <div class="ab_image">
          <img src="../assets/images/bg.png" alt="">
        </div>
        <div class="ab_father">
          <div>
            <div class="ab_title">
              Наши компетенции
            </div>
            <p class="ab_desc">
              Мы разрабатываем и интегрируем сложные высоконагруженные проекты для крупного бизнеса. Наши проекты
              повышают продажи и упрощают жизнь людей.
            </p>
            <p class="ab_desc">
              Мы не любим тяжеловесные интерфейсы и ядовитый дизайн, в проектах используем понятие «нетоксичности». Для
              нас важно, чтобы сайты говорили на одном языке с пользователем, поэтому день за днем мы создаем новую
              комфортную модель поведения пользователя.
            </p>
          </div>
          <div class="ab_links">
            <div class="likn_about">
              <router-link to="/">личные кабинеты</router-link>
            </div>
            <div class="likn_about">
              <router-link to="/">support 24/7</router-link>
            </div>
            <div class="likn_about">
              <router-link to="/">финансовый сектор</router-link>
            </div>
            <div class="likn_about">
              <router-link to="/">личные кабинеты</router-link>
            </div>
            <div class="likn_about">
              <router-link to="/">support 24/7</router-link>
            </div>
            <div class="likn_about">
              <router-link to="/">финансовый сектор</router-link>
            </div>
          </div>
        </div>
      </section>
    </div>
    <section class="bg_abouts">
      <div class="about_content">
        <div class="container">
          <div class="row mb-5">
            <div class="col-md-2">

            </div>
            <div class="col-md-10">
              <div class="abo_title">
                Мы являемся комплексным партнером по дизайну и технологиям в эпоху цифровых технологий. Мы помогаем
                предприятиям внедрять инновации и оставаться актуальными для своих клиентов, разрабатывая передовые
                цифровые продукты и осуществляя интеллектуальную и ценную коммуникацию.
              </div>
              <div class="row">
                <div class="col-md-6">
                <div class="statistic1">
                  30
                </div>
                  <div class="st_title">
                    Лет в бизнесе
                  </div>
                </div>
                <div class="col-md-6 " >
                  <div class="statistic1">
                    30
                  </div>
                  <div class="st_title">
                    Лет в бизнесе
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="statistic1 active">
                    30
                  </div>
                  <div class="st_title active">
                    Члены команды
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="statistic1 active">
                    30
                  </div>
                  <div class="st_title active">
                    Реализованные проекты
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <router-link to="/" v-for="item in 5" :key="item">
          <div class="image_cards_about">
            <img src="../assets/images/unspl.png" alt="">
            <div class="title_abouts">
              <div class="image_card_title">Jamshid</div>
              <div class="image_cards_description">Ceo</div>
            </div>
          </div>
        </router-link>
      </div>
    </section>
    <div class="container">
      <div class="section_three mt-4">
        <h3>Мы воплощаем в жизнь наших
          клиентов новые технологии</h3>
        <router-link to="/">

          <svg width="144" height="144" viewBox="0 0 144 144" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="72" cy="72" r="71.5" stroke="white"/>
            <path
                d="M96.3942 57.6821L47.1072 86.138M96.3942 57.6821C88.8361 64.5101 84.9745 69.204 85.0256 80.6748M96.3942 57.6821C86.7019 60.8136 80.7061 61.8109 70.7977 56.0313"
                stroke="white" stroke-width="1.4"/>
          </svg>

        </router-link>
      </div>

      <div class="row">
        <div class="col-md-2 images_groups" v-for="(item,index1) in 18" :key="index1">
          <router-link to="/">
            <img src="../assets/images/image15.png" alt="">
          </router-link>
        </div>
      </div>
      <div class="section_three">
        <swiper class="swiper" :options="swiperOption">
          <swiper-slide v-for="(item,index3) in 5" :key="index3">
            <router-link to="/" class="main_cards">
              <div class="card_head">
                <img src="../assets/images/Ellipse.png" alt="">
                <div>
                  <div class="name">Бахадиров Ибрагим</div>
                  <div class="sure_name">Директор Artel Групп</div>
                </div>
              </div>
              <div class="card_body">
                <div class="sv_description">
                  Информационные технологии — отрасль, в которой хотят работать многие. Программирование,
                  тестирование, администрирование, аналитика — эти и другие направления востребованы в сфере ИТ. В
                  восприятии одних, работа в ИТ-компании — работа мечты, но и рутина глазами других
                </div>
              </div>
            </router-link>
          </swiper-slide>
        </swiper>
      </div>

      <div class="row mb-5">
        <div class="col-md-12 mb-5 ">
          <div class="row f_main mb-5">
            <div class="col-md-6 col-12  main_subscribe">
              <div>
                <div>
                  <h3 class="title_section tit_m">
                    Оставьте
                    заявку</h3>
                </div>
                <div class="ms_description">
                  Расскажите о проекте и задний
                  вопросы - мы скоро ответим
                </div>
              </div>
              <div class="main_data">
                <div class="phone">+998 97 666 66 66</div>
                <div class="phone">info@ndc.uz</div>
              </div>
            </div>
            <div class="col-md-6 col-12  main_subscribe2">
              <div class="input-group">
                <form @submit.prevent="">
                  <div class="f_group">
                    <div class="input_father">
                      <input type="text" placeholder="Имя">
                    </div>
                    <div class="input_father">
                      <input type="text" placeholder="Имя">
                    </div>
                  </div>
                  <div class="input_father in_d">
                    <input type="text" placeholder="Имя">
                  </div>
                  <div class="in_title">О проекте</div>
                  <div class="input_father in_description_on">
                    <a href="#" class="bt_input">Веб-разработка</a>
                    <a href="#" class="bt_input">Реклама</a>
                    <a href="#" class="bt_input">Брендинг</a>
                  </div>
                  <div class="input_father in_description_on">
                    <input type="text" placeholder="Имя">
                  </div>
                  <div class="btn_father">
                    <button class="form_btn">

                      <svg width="200" height="200" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <circle cx="100" cy="100" r="99.5" stroke="white"/>
                        <path d="M133.881 80.1135L65.4263 119.636M133.881 80.1135C123.383 89.5969 118.02 96.1162 118.091 112.048M133.881 80.1135C120.419 84.4629 112.091 85.848 98.3297 77.8208" stroke="white" stroke-width="1.4"/>
                      </svg>

                    </button>

                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <Footer></Footer>
  </div>
</template>
<script>

import Navbar from "../components/Navbar";
import {Swiper, SwiperSlide} from 'vue-awesome-swiper'
import "swiper/swiper-bundle.min.css"
import Footer from "../components/Footer";

export default {
  name: 'Home',
  components: {
    Footer,
    Navbar,
    Swiper,
    SwiperSlide

  },
  data() {
    return {
      swiperOption: {
        slidesPerView: 3,
        spaceBetween: 30,
        freeMode: true,
        pagination: {
          el: '.swiper-pagination',
          clickable: true
        }
      }
    }
  }
}
</script>
