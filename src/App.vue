<template>
  <div id="app">
    <div class="background_container" id="about">
      <div class="wrapper">
        <header-app/>

        <promo-app/>

        <about-me-app/>

        <portfolio-app/>

        <section class="technologies" id="skills">
          <div class="technologies__container">
            <div class="technologies page-parts">
              <h4 class="technologies page-parts__text">👨‍💻 Skills</h4>
            </div>
            <h2 class="technologies__title">Technologies and skills</h2>
            <div class="technologies__block">
              <img src="../icons/Javascript.svg" alt="Javascript" class="technologies__block__icon">
              <img src="../icons/TypeScript.svg" alt="TypeScript" class="technologies__block__icon">
              <img src="../icons/Vue.svg" alt="vue" class="technologies__block__icon">
              <img src="../icons/vuex-store.svg" alt="Vue x" class="technologies__block__icon">
              <img src="../icons/vuetify.svg" alt="Vuetify" class="technologies__block__icon">
              <img src="../icons/css.svg" alt="css" class="technologies__block__icon">
              <img src="../icons/sass.svg" alt="sass" class="technologies__block__icon">
              <img src="../icons/html.svg" alt="html" class="technologies__block__icon">
              <img src="../icons/bootstrap-4.svg" alt="bootstrap" class="technologies__block__icon">
              <img src="../icons/Github_tech.svg" alt="github" class="technologies__block__icon">
              <img src="../icons/git.svg" alt="git" class="technologies__block__icon">
              <img src="../icons/Figma.svg" alt="Figma" class="technologies__block__icon">
              <img src="../icons/Insomnia.svg" alt="Insomnia" class="technologies__block__icon">
              <img src="../icons/Nodejs.svg" alt="Nodejs" class="technologies__block__icon">
            </div>
          </div>
        </section>
        <section class="career" id="career">
          <div class="career__container">
            <div class="career page-parts">
              <h4 class="career page-parts__text">💼 Career</h4>
            </div>
            <h2 class="career__title">Previous job</h2>
            <div class="career__box">
              <div class="career__box__card">
                <div class="card__header">
                  <h4 class="card__header__title">Com'ngo</h4>
                  <img src="../icons/_.png" alt="comn'go logo" class="card__header__logo">
                </div>
                <a href="https://comngo.online/" class="card__link">Visit website</a>
                <p class="card__desr">Development of complex information systems using microfronted for travel agencies with support for multi-localization.
                  <br><br>
                  Technology stack:
                  <br><br>
                  - HTML, CSS, SCSS;<br>
                  - Vue;<br>
                  - vuex, vue router, i18n;<br>
                  - JavaScript (JS), TypeScript (TS);<br>
                  - bootstrap Vue and vuetify;<br>
                  - Node.js;<br>
                  - Git (GitLab);<br>
                  Integration with various services and APIs;<br>
                  <br>
                  Setting up localization for 3 languages with rtl support (English, Hebrew, Russian);<br>
                  <br>
                  Layout using HTML5 CSS3 SCSS and ready-made UI kit, Figma.<br></p>
                <div class="card__footer">
                  <p class="card__footer__term">
                    5 month
                  </p>
                  <p class="card__footer__time">
                    June/2023 - October/2023
                  </p>
                </div>
              </div>
            </div>
            <div class="career__box">
              <div class="career__box__card">
                <div class="card__header">
                  <h4 class="card__header__title">Tinkoff Bank</h4>
                  <img src="../icons/tinkoff.svg" alt="comn'go logo" class="card__header__logo">
                </div>
                <a href="https://www.tinkoff.ru/" class="card__link">Visit website</a>
                <p class="card__desr">Administration of the training portal for Tinkoff employees:
                  <br><br>
                  - Layout and editing of portal sections, pages, articles, courses;<br>
                  - Working with accounts of employees, candidates;<br>
                  - Editing pages of the educational portal;<br>
                  - Tabular layout of letters;<br>
                  - Analysis and collection of statistics on the completion of training plans by employees;<br>
                  - Working with the database;<br>
                  - Execution of project tasks.</p>
                <div class="card__footer">
                  <p class="card__footer__term">
                    1 year 3 month
                  </p>
                  <p class="card__footer__time">
                    March/2022 - May/2023
                  </p>
                </div>
              </div>
            </div>
            <div class="career__box" id="career">
              <div class="career__box__card">
                <div class="card__header">
                  <h4 class="card__header__title">Ufanet</h4>
                  <img src="../icons/ufanet.svg" alt="comn'go logo" class="card__header__logo">
                </div>
                <a href="https://www.ufanet.ru/" class="card__link">Visit website</a>
                <p class="card__desr">Construction of intercom systems (“Smart Intercom”):<br><br>
                  - Connection, system configuration;<br>
                  - Connecting and setting up equipment;<br>
                  - Installation and connection of video surveillance:<br>
                  - Connecting subscribers to the network;<br>
                  - Records management;<br>
                  - Search and analysis of faults in the system;<br>
                  - Trouble-shooting;<br>
                  - Responding to user requests.<br></p>
                <div class="card__footer">
                  <p class="card__footer__term">
                    9 month
                  </p>
                  <p class="card__footer__time">
                    November/2020 - July/2021
                  </p>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section class="recommend" id="recommendation">
          <div class="recommend__container">
            <div class="recommend page-parts">
              <h4 class="recommend page-parts__text">💬 Recommend</h4>
            </div>
            <h2 class="recommend__title">Recommended by managers</h2>
            <div class="recommend__box">
              <div class="recommend__box__card">
                <img src="../icons/tinkoff.svg" alt="Tinkoff logo" class="card__company-logo">
                <div class="card__body">
                  <img src="../icons/user_logo.svg" alt="card photo" class="card__photo">
                  <div class="card__person">
                    <h4 class="card__person__name">Sergey Usenko</h4>
                    <p class="card__person__position">Teamlead</p>
                  </div>
                </div>
              </div>
              <div class="recommend__box__card">
                <img src="../icons/_.png" alt="Tinkoff logo" class="card__company-logo">
                <div class="card__body">
                  <img src="../icons/user_logo.svg" alt="card photo" class="card__photo">
                  <div class="card__person">
                    <h4 class="card__person__name">Alexander Shaikevich</h4>
                    <p class="card__person__position">CEO</p>
                  </div>
                </div>
              </div>
              <div class="recommend__box__card">
                <img src="../icons/_.png" alt="Tinkoff logo" class="card__company-logo">
                <div class="card__body">
                  <img src="../icons/user_logo.svg" alt="card photo" class="card__photo">
                  <div class="card__person">
                    <h4 class="card__person__name">Mansur Zakirov</h4>
                    <p class="card__person__position">Teamlead</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section class="contacts" id="contacts">
          <div class="contacts__container">
            <div class="contacts page-parts">
              <h4 class="contacts page-parts__text">📬 Contacts</h4>
            </div>
            <h2 class="contacts__title">Write me!</h2>
            <div class="contacts__box">
              <a href="https://kazan.hh.ru/resume/88e02d45ff0908c6be0039ed1f446b50496231" class="contacts__box_link">
                <button class="contacts__box connection-btn">
                  <h4 class="connection-btn__text">Open CV on HH.ru</h4>
                </button>
              </a>
              <div class="contacts__box__mail">
                <div>
                  <a href="https://t.me/Marlontis" class="mail__telegram">Text in Telegram<img src="../icons/PaperPlaneTilt.svg" alt="Paper Plane icon"></a>
                </div>
                <p class="mail__text">E-mail:</p>
                <a href= "mailto:markgirfanov@gmail.com" class="mail__adress">markgirfanov@gmail.com</a>
              </div>
            </div>
          </div>
        </section>
      </div>
    </div>
    <footer class="footer">
      <div class="footer__container">
        <div class="footer__social-network">
          <a href="https://github.com/Markelas"><img src="../icons/github.png" alt="github-icon" class="footer__social-network__icon"></a>
          <a href="https://t.me/Marlontis"><img src="../icons/telegram.png" alt="telegram-icon" class="footer__social-network__icon"></a>
          <a href="https://vk.com/markeellas"><img src="../icons/vk.png" alt="vk-icon" class="footer__social-network__icon"></a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>

import HeaderApp from "@/components/HeaderApp.vue";
import PromoApp from "@/components/PromoApp.vue";
import AboutMeApp from "@/components/AboutMeApp.vue";
import PortfolioApp from "@/components/PortfolioApp.vue";

export default {
  components: {PortfolioApp, HeaderApp, PromoApp, AboutMeApp}

}
</script>

<style lang="scss">

</style>
