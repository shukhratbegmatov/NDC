<template>
  <div class="home">
    <header class="header_bg">
      <div class="container">

        <Navbar></Navbar>
        <div class="content">
          <div class="content_child">
            <div class="content_text">
              Крупнейший интегратор
            </div>
            <div class="content_title">
              digital‑решений
            </div>
            <div class="content_description">
              Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
              превращается в потребительский опыт
            </div>
          </div>
          <a href="#" class="btn_link mt-4">

            <svg width="200" height="200" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="100" cy="100" r="99.5" stroke="white"/>
              <path
                  d="M133.881 80.1135L65.4263 119.636M133.881 80.1135C123.383 89.5969 118.02 96.1162 118.091 112.048M133.881 80.1135C120.419 84.4629 112.091 85.848 98.3297 77.8208"
                  stroke="white" stroke-width="1.4"/>
            </svg>

          </a>
        </div>

      </div>
      <div class="ani_mous">
        <span>
        <svg width="38" height="66" viewBox="0 0 38 66" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect x="0.3" y="0.3" width="37.4" height="65.4" rx="18.7" stroke="white" stroke-width="0.6"/>
        <circle opacity="0.8" cx="19" cy="50" r="4" fill="white"/>
        </svg>
        </span>
      </div>
    </header>
    <section class="section_one">
      <div class="container pt-5" v-for="(item,index) in 4" :key="index">
        <div class="portfoliyo">
          <div>
            <h1 class="port_title">Таможенная карта</h1>
          </div>
          <div class="port_links">
            <router-link to="/" class="port_link ">Разработка</router-link>
            <router-link to="/" class="port_link ">SEO оптимизация</router-link>
            <router-link to="/" class="port_link ">Брендинг</router-link>
            <router-link to="/" class="port_link active city_links">
              www.container.com
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M8.63905 6.54297C8.22484 6.54297 7.88905 6.87876 7.88905 7.29297C7.88905 7.70718 8.22484 8.04297 8.63905 8.04297V6.54297ZM16.7191 7.29297H17.4691C17.4691 6.87876 17.1333 6.54297 16.7191 6.54297V7.29297ZM15.9691 15.372C15.9691 15.7862 16.3048 16.122 16.7191 16.122C17.1333 16.122 17.4691 15.7862 17.4691 15.372H15.9691ZM6.77472 16.1766C6.48183 16.4695 6.48183 16.9444 6.77472 17.2373C7.06762 17.5302 7.54249 17.5302 7.83538 17.2373L6.77472 16.1766ZM17.2374 7.8353C17.5303 7.54241 17.5303 7.06753 17.2374 6.77464C16.9445 6.48175 16.4696 6.48175 16.1767 6.77464L17.2374 7.8353ZM8.63905 8.04297H16.7191V6.54297H8.63905V8.04297ZM15.9691 7.29297V15.372H17.4691V7.29297H15.9691ZM7.83538 17.2373L17.2374 7.8353L16.1767 6.77464L6.77472 16.1766L7.83538 17.2373Z"
                    fill="white"/>
              </svg>
            </router-link>
          </div>
        </div>
        <div class="content_images">
          <img src="../assets/images/image.png" alt="">
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
    </section>

    <section class="section_two">
      <div class="container">
        <div class="initiators">
          <h3>
            Мы -<span>инициаторы!</span>
          </h3>
        </div>
        <div class="row">
          <div class="col-md-6">
            <p class="initiators_title">
              Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
              превращается в потребительский опыт.
            </p>
          </div>
          <div class="col-md-6">
            <p class="cards_one">
              Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
              превращается в потребительский опыт.
            </p>
            <p class="cards_one">
              Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
              превращается в потребительский опыт.
            </p>
          </div>
          <div class="col-md-6 col-12">
            <div class="initiators_cards">
              <div class="initiators_cards_head">
                <div class="initiators_cards_title">Учебный центр It Unity</div>
                <router-link to="/" class="port_link active city_links">
                  www.container.com
                  <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M8.63905 6.54297C8.22484 6.54297 7.88905 6.87876 7.88905 7.29297C7.88905 7.70718 8.22484 8.04297 8.63905 8.04297V6.54297ZM16.7191 7.29297H17.4691C17.4691 6.87876 17.1333 6.54297 16.7191 6.54297V7.29297ZM15.9691 15.372C15.9691 15.7862 16.3048 16.122 16.7191 16.122C17.1333 16.122 17.4691 15.7862 17.4691 15.372H15.9691ZM6.77472 16.1766C6.48183 16.4695 6.48183 16.9444 6.77472 17.2373C7.06762 17.5302 7.54249 17.5302 7.83538 17.2373L6.77472 16.1766ZM17.2374 7.8353C17.5303 7.54241 17.5303 7.06753 17.2374 6.77464C16.9445 6.48175 16.4696 6.48175 16.1767 6.77464L17.2374 7.8353ZM8.63905 8.04297H16.7191V6.54297H8.63905V8.04297ZM15.9691 7.29297V15.372H17.4691V7.29297H15.9691ZM7.83538 17.2373L17.2374 7.8353L16.1767 6.77464L6.77472 16.1766L7.83538 17.2373Z"
                        fill="white"/>
                  </svg>
                </router-link>
              </div>
              <div class="initiators_cards_body">
                <p class="initiators_cards_description">
                  Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
                  превращается в потребительский опыт.
                </p>
                <div class="main_father">
                  <div>
                    <img class="image1" src="../assets/images/main-top.png" alt="">
                    <img class="image_3" src="../assets/images/Group.png" alt="">
                  </div>
                  <div>
                    <img class="image2" src="../assets/images/main-top-2.png" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-12">
            <div class="main_two_card">
              <div class="initiators_cards_head">
                <div class="initiators_cards_title">Флиланс биржа - HireLancer</div>
                <router-link to="/" class="port_link active city_links">
                  www.container.com
                  <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M8.63905 6.54297C8.22484 6.54297 7.88905 6.87876 7.88905 7.29297C7.88905 7.70718 8.22484 8.04297 8.63905 8.04297V6.54297ZM16.7191 7.29297H17.4691C17.4691 6.87876 17.1333 6.54297 16.7191 6.54297V7.29297ZM15.9691 15.372C15.9691 15.7862 16.3048 16.122 16.7191 16.122C17.1333 16.122 17.4691 15.7862 17.4691 15.372H15.9691ZM6.77472 16.1766C6.48183 16.4695 6.48183 16.9444 6.77472 17.2373C7.06762 17.5302 7.54249 17.5302 7.83538 17.2373L6.77472 16.1766ZM17.2374 7.8353C17.5303 7.54241 17.5303 7.06753 17.2374 6.77464C16.9445 6.48175 16.4696 6.48175 16.1767 6.77464L17.2374 7.8353ZM8.63905 8.04297H16.7191V6.54297H8.63905V8.04297ZM15.9691 7.29297V15.372H17.4691V7.29297H15.9691ZM7.83538 17.2373L17.2374 7.8353L16.1767 6.77464L6.77472 16.1766L7.83538 17.2373Z"
                        fill="white"/>
                  </svg>
                </router-link>
              </div>

              <p class="initiators_cards_description description">
                Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
                превращается в потребительский опыт.
              </p>
              <div class="images_group">
                <div>
                  <img class="image_2" src="../assets/images/Mask.png" alt="">
                </div>
                <div>
                  <img class="image_1" src="../assets/images/iphone.png" alt="">
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-12">
            <div class="main_two_card change_bg">
              <div class="initiators_cards_head">
                <div class="initiators_cards_title">Флиланс биржа - HireLancer</div>
                <router-link to="/" class="port_link active city_links">
                  www.container.com
                  <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M8.63905 6.54297C8.22484 6.54297 7.88905 6.87876 7.88905 7.29297C7.88905 7.70718 8.22484 8.04297 8.63905 8.04297V6.54297ZM16.7191 7.29297H17.4691C17.4691 6.87876 17.1333 6.54297 16.7191 6.54297V7.29297ZM15.9691 15.372C15.9691 15.7862 16.3048 16.122 16.7191 16.122C17.1333 16.122 17.4691 15.7862 17.4691 15.372H15.9691ZM6.77472 16.1766C6.48183 16.4695 6.48183 16.9444 6.77472 17.2373C7.06762 17.5302 7.54249 17.5302 7.83538 17.2373L6.77472 16.1766ZM17.2374 7.8353C17.5303 7.54241 17.5303 7.06753 17.2374 6.77464C16.9445 6.48175 16.4696 6.48175 16.1767 6.77464L17.2374 7.8353ZM8.63905 8.04297H16.7191V6.54297H8.63905V8.04297ZM15.9691 7.29297V15.372H17.4691V7.29297H15.9691ZM7.83538 17.2373L17.2374 7.8353L16.1767 6.77464L6.77472 16.1766L7.83538 17.2373Z"
                        fill="white"/>
                  </svg>
                </router-link>
              </div>

              <p class="initiators_cards_description description">
                Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
                превращается в потребительский опыт.
              </p>
              <div class="images_group">
                <div>
                  <img class="image_2" src="../assets/images/Mask.png" alt="">
                </div>
                <div>
                  <img class="image_1" src="../assets/images/iphone.png" alt="">
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-12">
            <div class="initiators_cards3">
              <div class="initiators_cards_child">
                <div class="initiators_cards3_title">
                  Флиланс биржа - HireLancer
                </div>
                <div class="initiators_cards3_description">
                  Понимаем, как эмоции в digital становятся впечатлениями, а рациональный результат взаимодействия
                  превращается в потребительский опыт.
                </div>
                <div class="initiators_cards_scoro">
                  СКОРО
                </div>
              </div>
              <img src="../assets/images/img.png" alt="" class="image_vec">

            </div>
          </div>
        </div>
      </div>

    </section>

    <section class="section_three">
      <div class="container">
        <div class="section_three">
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
        <h3 class="title_section">Отзывы</h3>

          <VueSlickCarousel v-bind="settings" ref="carousel">
            <div  >
              <div class="main_cards">
                <router-link to="/">
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
              </div>

            </div>
            <div  >
              <div class="main_cards">
                <router-link to="/">
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
              </div>

            </div>
            <div  >
              <div class="main_cards">
                <router-link to="/">
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
              </div>

            </div>
            <div  >
              <div class="main_cards">
                <router-link to="/">
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
              </div>

            </div>
          </VueSlickCarousel>

        <div class="col-md-12 sw_father">
          <div class="sw_buttons">
            <button ref="nextEl" class="prev" id="prev">
              <img @click="prewsw()" src="../assets/icons/next.svg" alt="">
            </button>
            <button ref="prevEl" @click="nextsw()" class="next" id="next">
              <img src="../assets/icons/prev.svg" alt="">
            </button>
          </div>
        </div>

        <div class="section_next">
          <div>
            <h3 class="title_section">Новости</h3>
          </div>
          <div>
            <router-link to="/" class="link1">Все новости</router-link>
          </div>

        </div>
        <div class="row">
          <div class="col-md-4" v-for="(item,index3) in 3" :key="index3">
            <router-link to="/" class="main_card_father">
              <div class="main_card1">
                <div class="m_images">
                  <img src="../assets/images/Rectangle.png" alt="">
                </div>
                <div class="date">
                <span>
                  <svg width="16" height="17" viewBox="0 0 16 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M3 4.23771C3 3.62857 3.4938 3.13477 4.10294 3.13477H11.8971C12.5062 3.13477 13 3.62857 13 4.23771V12.4833C13 13.0924 12.5062 13.5862 11.8971 13.5862H4.10294C3.4938 13.5862 3 13.0924 3 12.4833V4.23771Z" stroke="white" stroke-width="1.10294" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M10 2.07422V4.37968" stroke="white" stroke-width="1.10294" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M6 2.07422V4.37968" stroke="white" stroke-width="1.10294" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M3 6.27051H13" stroke="white" stroke-width="1.10294" stroke-linecap="round" stroke-linejoin="round"/>
                  </svg>
                  14.09.2020
                </span>
                  <span>

                  <svg width="16" height="17" viewBox="0 0 16 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M1.71484 8.21139C1.71484 8.21139 4.00056 3.43359 8.00056 3.43359C12.0006 3.43359 14.2863 8.21139 14.2863 8.21139C14.2863 8.21139 12.0006 12.9892 8.00056 12.9892C4.00056 12.9892 1.71484 8.21139 1.71484 8.21139Z" stroke="white" stroke-width="1.14286" stroke-linecap="round" stroke-linejoin="round"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M7.99944 10.0033C8.94622 10.0033 9.71373 9.20111 9.71373 8.2116C9.71373 7.22208 8.94622 6.41992 7.99944 6.41992C7.05267 6.41992 6.28516 7.22208 6.28516 8.2116C6.28516 9.20111 7.05267 10.0033 7.99944 10.0033Z" stroke="white" stroke-width="1.14286" stroke-linecap="round" stroke-linejoin="round"/>
                  </svg>
                2020
                </span>
                </div>
                <div class="m_title">
                  Бугундан бирламчи тиббиёт муассасаларида ортиқча қоғозбозликка чек қўйилиб, янги тартибда иш юритилади
                </div>
                <div class="m_description">
                  Поликлиникаларда юритиладиган 26 турдаги тиббий ҳисоб журналларидан 14 таси қолдирилди. Қолган 14
                  тасидан 10 таси соддалаштирилди.
                </div>

              </div>
            </router-link>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12 mb-5 ">
            <div class="row f_main mb-5">
              <div class="col-md-6 col-12 mb-5  main_subscribe">
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
    </section>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
import Navbar from "../components/Navbar";
import Footer from "../components/Footer";
export default {
  name: 'Home',
  components: {
    Footer,
    Navbar,
    VueSlickCarousel

  },
  data() {
    return {
      settings:{
        "dots": false,
        "focusOnSelect": false,
        "infinite":true,
        "speed": 500,
        "slidesToShow": 3,
        "slidesToScroll": 1,
        "touchThreshold": 5,
        'autoplay':true,
        'autoplaySpeed':1500
      },
    }
    },
  methods:{
    nextsw(){
      this.$refs.carousel.next()
    },
    prewsw()
    {
      this.$refs.carousel.prev()
    }

  },

}
</script>
