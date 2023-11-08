<template>
  <div id="app">
    <body>
    <div class="background_container" id="about">
      <div class="wrapper">
        <header>
          <div class="header_container">
            <nav class="navigation">
              <img src="../icons/laptop.png" alt="laptop-icon" class="navigation__icon">
              <ul class="navigation__menu">
                <li class="menu__item"><a href="#home" class="menu__item-link--active">Home</a></li>
                <li class="menu__item"><a href="#aboutMe" class="menu__item-link">About me</a></li>
                <li class="menu__item"><a href="#portfolio" class="menu__item-link">Portfolio</a></li>
                <li class="menu__item"><a href="#skills" class="menu__item-link">Skills</a></li>
                <li class="menu__item"><a href="#career" class="menu__item-link">Career</a></li>
                <li class="menu__item"><a href="#recommendation" class="menu__item-link">Recommendation</a></li>
                <li class="menu__item"><a href="#contacts" class="menu__item-link">Contacts</a></li>
              </ul>
            </nav>
          </div>
        </header>
        <section class="promo">
          <div class="promo__container">
            <div class="promo__info">
              <div class="promo page-parts">
                <h4 class="promo page-parts__text">👋 Hello!</h4>
              </div>
              <h1 class="promo__name">Girfanov Mark</h1>
              <div class="promo__profession">Front-end developer</div>
              <div class="promo__social-network">
                <a href="https://github.com/Markelas"><img src="../icons/github.png" alt="github-icon" class="social-network__icon"></a>
                <a href="https://t.me/Marlontis"><img src="../icons/telegram.png" alt="telegram-icon" class="social-network__icon"></a>
                <a href="https://vk.com/markeellas"><img src="../icons/vk.png" alt="vk-icon" class="social-network__icon"></a>
              </div>
            </div>
            <img src="../images/Mark.png" alt="Mark_img" class="promo__logo">
            <div class="promo__links">
              <a href="https://kazan.hh.ru/resume/88e02d45ff0908c6be0039ed1f446b50496231">
                <button class="promo__links connection-btn">
                  <h4 class="connection-btn__text">Open CV on HH.ru</h4>
                </button>
              </a>
            </div>
          </div>
        </section>
        <section class="about-me" id="aboutMe">
          <div class="about-me__container">
            <div class="about-me__photo">
              <img src="../images/ProfilePic.png" alt="photo" class="photo__my-photo">
            </div>
            <div class="about-me__info">
              <div class="about-me page-parts">
                <h4 class="about-me page-parts__text">🧐 About me</h4>
              </div>
              <h2 class="about-me__info__name">Girfanov Mark</h2>
              <div class="about-me__info__descr">
                <p class="about-me__info__descr__text"> 🎓 Education: Kazan National Research Technical University
                  named after A. N. Tupolev - KAI, Kazan<br>
                  💻 Specialty: Information Systems and Technologies.<br>
                  👨‍💻 Skills: I have been developing and programming interfaces for more than 2 years.<br>
                  🤖 Currently I use JavaScript, Typescript, Vue JS, Vuex, Vue Router, Vuetify, SCSS, Git.<br>
                  🚀 I try every day to be a little better than yesterday.<br>
                  🕗 In my spare time I like to paint 🎨 and go to the GYM 🏋️.
                </p>
              </div>
            </div>
          </div>
        </section>
        <section class="portfolio" id="portfolio">
          <div class="portfolio__container">
            <div class="promo page-parts">
              <h4 class="promo page-parts__text">🔗 Portfolio</h4>
            </div>
            <h2 class="portfolio__title">My projects</h2>
            <div class="portfolio__box">
              <a href="https://vue-crm-frontend-mark.web.app/">
                <div class="portfolio__box__card">
                  <h4 class="card__title">Vue js CRM system</h4>
                  <p class="card__desr">This is a CRM system (home accounting) for analyzing and accounting for expenses.</p>
                  <div class="card__tools">
                    <div class="card__tools__item--main">Vue js</div>
                    <div class="card__tools__item">Typescript</div>
                  </div>
                  <img src="../images/card_img/card_vue_crm.png" alt="vue_crm_img" class="card__img">
                </div>
              </a>
              <a href="https://vue-freelance-web-app-mark.web.app/">
                <div class="portfolio__box__card">
                  <h4 class="card__title">Vue js Freelance</h4>
                  <p class="card__desr">This is an application for finding freelance jobs. Here you can publish your new task or take it on the board with suggestions.</p>
                  <div class="card__tools">
                    <div class="card__tools__item--main">Vue js</div>
                    <div class="card__tools__item">JavaScript</div>
                  </div>
                  <img src="../images/card_img/card_vue_freelance.png" alt="vue_crm_img" class="card__img">
                </div>
              </a>
              <a href="https://vue-homework-8-mark.web.app/">
                <div class="portfolio__box__card">
                  <h4 class="card__title">Vue js resume constructor</h4>
                  <p class="card__desr">This is a resume constructor. Here you can put together your own resume.</p>
                  <div class="card__tools">
                    <div class="card__tools__item--main">Vue js</div>
                    <div class="card__tools__item">JavaScript</div>
                  </div>
                  <img src="../images/card_img/card_vue_resume.png" alt="vue_crm_img" class="card__img">
                </div>
              </a>
              <a href="https://vue-ts-todos.web.app/">
                <div class="portfolio__box__card">
                  <h4 class="card__title">Vue js Todos</h4>
                  <p class="card__desr">
                    This is a list of tasks where you can see current tasks and completed ones. You can also create a new task.</p>
                  <div class="card__tools">
                    <div class="card__tools__item--main">Vue js</div>
                    <div class="card__tools__item">JavaScript</div>
                  </div>
                  <img src="../images/card_img/card_vue_todos.png" alt="vue_crm_img" class="card__img">
                </div>
              </a>
              <a href="https://rolling-scopes-school.github.io/markelas-JSFEPRESCHOOL2022Q4/plants/pages/main/">
                <div class="portfolio__box__card">
                  <h4 class="card__title">Plants</h4>
                  <p class="card__desr">Website for a plant care company. The company is engaged in the cultivation, care and sale of plants. </p>
                  <div class="card__tools">
                    <div class="card__tools__item--main">JavaScript</div>
                    <div class="card__tools__item">HTML</div>
                    <div class="card__tools__item">CSS</div>
                  </div>
                  <img src="../images/card_img/card_plants.png" alt="vue_crm_img" class="card__img">
                </div>
              </a>
              <a href="https://rolling-scopes-school.github.io/markelas-JSFE2022Q1/shelter/pages/main/index.html">
                <div class="portfolio__box__card">
                  <h4 class="card__title">Cozy House</h4>
                  <p class="card__desr">Website for shelter. They offer to give a chance to a little and nice puppy with an extremely wide and open heart. He or she will love you more than anybody else in the world.</p>
                  <div class="card__tools">
                    <div class="card__tools__item--main">JavaScript</div>
                    <div class="card__tools__item">HTML</div>
                    <div class="card__tools__item">CSS</div>
                  </div>
                  <img src="../images/card_img/card_cozy_house.png" alt="vue_crm_img" class="card__img">
                </div>
              </a>
            </div>
          </div>
        </section>
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
    </body>
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

export default {

}
</script>

<style lang="scss">

</style>
