<template>
  <section class="career" id="career">
    <div class="career__container">
      <div class="career page-parts">
        <h4 class="career page-parts__text">💼 Career</h4>
      </div>
      <h2 class="career__title">Previous job</h2>
      <div class="career__wrapper--main-size">
        <div class="career__box">
          <div class="career__box__card">
            <div class="card__header">
              <h4 class="card__header__title">Com'ngo</h4>
              <img src="../../icons/_.png" alt="comn'go logo" class="card__header__logo">
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
              <img src="../../icons/tinkoff.svg" alt="comn'go logo" class="card__header__logo">
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
        <div class="career__box">
          <div class="career__box__card">
            <div class="card__header">
              <h4 class="card__header__title">Ufanet</h4>
              <img src="../../icons/ufanet.svg" alt="comn'go logo" class="card__header__logo">
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
      <swiper-career-app class="career__wrapper--carousel"/>
    </div>
  </section>
</template>

<script>
import SwiperCareerApp from "@/components/swiperDir/swiperCareerApp.vue";

export default {
  name: "CareerApp",
  components: {SwiperCareerApp},
}
</script>

<style scoped>
.career__wrapper--carousel{
  display: none;
}
@media (max-width: 600px) {
  .career{
    display: block;
    .career__title{
      margin-bottom: 5px;
    }
  }
  .career__wrapper--main-size{
    display: none;
  }
  .career__wrapper--carousel{
    display: block;
  }
}
</style>
