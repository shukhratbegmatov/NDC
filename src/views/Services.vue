<template>
    <div class="bg_main">
        <div class="container">
          <Navbar></Navbar>
          <section class="s_section">
            <div class="f_main_text">
              <div>
                <h3>Услуги</h3>
              </div>
              <div class="content_description">
                Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
                превращается в потребительский опыт
              </div>
            </div>
            <div class="row">
              <div class="col-md-4" v-for="(item,index2) in 3" :key="index2">
                <router-link to="/" class="ser_card">
                  <div class="ser_main_card">

                    <div class="ser_title">
                      Контекстная реклама  яндекс и гугл
                    </div>
                    <div class="ser_description">
                      Понимаем, как эмоции в digital становятся впечатлениями,  рациональный результат взаимодействия превращается потребительский опыт
                    </div>
                    <div class="btn_ser_group">
                      <div class="ser_price">
                        от 1000$
                      </div>
                      <div class="ser_btn">
                        <svg width="168" height="168" viewBox="0 0 168 168" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <circle cx="84" cy="84" r="83.5" stroke="white"/>
                          <path d="M112.46 67.2954L54.9583 100.494M112.46 67.2954C103.642 75.2614 99.1368 80.7376 99.1963 94.1202M112.46 67.2954C101.152 70.9488 94.157 72.1123 82.5971 65.3694" stroke="white" stroke-width="1.4"/>
                        </svg>
                      </div>
                    </div>
                  </div>
                </router-link>
              </div>
            </div>
            <div class="contents_btn">
              <router-link to="/">

                <svg width="200" height="200" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <circle cx="100" cy="100" r="99.5" stroke="white"/>
                  <path
                      d="M90.6807 88.9984C96.7567 82.9224 106.606 82.9224 112.682 88.9984C118.758 95.0744 118.758 104.923 112.682 110.999C106.606 117.075 96.7544 117.075 90.6807 110.999L82.7614 103.08M82.7614 103.08V114.322M82.7614 103.08H94.0034"
                      stroke="white" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round"
                      stroke-linejoin="round"/>
                </svg>

              </router-link>
            </div>

            <div class="row">
              <div class="col-md-12 ">
                <div class="row f_main">
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
          </section>
        </div>
      <Footer></Footer>
      </div>
</template>
<script>
import Navbar from "../components/Navbar";
import Footer from "../components/Footer";
export default {
  components: {Footer, Navbar}
}
</script>
