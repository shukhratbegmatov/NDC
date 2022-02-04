
<template>
  <div class="bg_main">
    <div class="container">
      <Navbar></Navbar>
      <section class="s_section">
        <div class="f_main_text">
          <div>
            <h3>Будем рады быть с вами на связи!</h3>
          </div>
          </div>
        <div class="col-12 maps_bg">
          <div class="contact_form">
              <div class="row">
                <div class="col-md-6">
                  <div class="contact_title">Телефон</div>
                  <div class="contact_number">+998 97 571 66 66</div>
                </div>
                <div class="col-md-6">
                  <div class="contact_title">Общие вопросы</div>
                  <div class="contact_number">info@ndc.uz</div>
                </div>
                <div class="col-md-6">
                  <div class="contact_title">Адрес</div>
                  <div class="contact_number">Узбекистан, Ташкентский
                    Сергелийский район</div>
                </div>
                <div class="col-md-6">
                  <div class="contact_title">PR и мероприятия</div>
                  <div class="contact_number">pr@buroburo.ru</div>
                </div>
              </div>
            <div >
              <form @submit.prevent="">
                <div class="col-md-12 contact_input_group">
                    <input type="text" placeholder="Имя">
                </div>
                <div class="col-md-12 contact_input_group">
                  <input type="text" placeholder="Имя">
                </div>
                <div class="col-md-12 contact_input_group">
                  <input type="text" placeholder="Имя">
                </div>
                <div class="col-md-12 contact_input_group">
                  <input type="text" placeholder="Имя">
                </div>
                <div class="radio_group">
                  <div class="radio_child">
                    <div>
                      <input type="radio" id="checked">
                    </div>
                    <div>
                      <label for="checked">Настоящим подтверждаю, что я ознакомлен и согласен с политикой обработки персональных данных</label>
                    </div>
                  </div>
                  <div class="contact_btn">
                      <button>

                        <svg width="141" height="141" viewBox="0 0 141 141" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <circle cx="70.5" cy="70.5" r="70" stroke="#0F0F0F"/>
                          <path d="M94.3857 56.48L46.1255 84.343M94.3857 56.48C86.985 63.1658 83.2039 67.7618 83.2539 78.9936M94.3857 56.48C84.8953 59.5462 79.0244 60.5228 69.3224 54.8636" stroke="#0F0F0F" stroke-width="1.4"/>
                        </svg>

                      </button>
                  </div>
                </div>
              </form>
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

