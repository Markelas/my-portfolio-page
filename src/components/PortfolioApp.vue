<template>
  <section class="portfolio" id="portfolio">
    <div class="portfolio__container">
      <div class="portfolio page-parts">
        <h4 class="portfolio page-parts__text">🔗 Portfolio</h4>
      </div>
      <h2 class="portfolio__title">My projects</h2>
      <div class="portfolio__box">
        <div class="portfolio__box__card" v-for="card in cardsInfo" :key="card.id">
          <a :href='card.cardLink'>
            <h4 class="card__title">{{card.title}}</h4>
            <p class="card__desr">{{card.descr}}</p>
            <div class="card__tools">
              <div class="card__tools__item--main">{{card.toolsMain}}</div>
              <div class="card__tools__item" v-for="tool in card.toolsSecond" :key="tool">{{tool}}</div>
            </div>
            <img :src='card.img' class="card__img" :alt='card.title'>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "PortfolioApp",
  data() {
    return {
      cardsInfo:[
        {
          id: 1,
          title : 'Vue js CRM system',
          cardLink: 'https://vue-crm-frontend-mark.web.app/',
          descr: 'This is a CRM system (home accounting) for analyzing and accounting for expenses.',
          toolsMain: 'Vue js',
          toolsSecond: ['Typescript'],
          img: require('/images/card_img/card_vue_crm.png')
        },
        {
          id: 2,
          title : 'Vue js Freelance',
          cardLink: 'https://vue-freelance-web-app-mark.web.app/',
          descr: 'his is an application for finding freelance jobs. Here you can publish your new task or take it on the board with suggestions.',
          toolsMain: 'Vue js',
          toolsSecond: ['JavaScript'],
          img: require('/images/card_img/card_vue_freelance.png')
        },
        {
          id: 3,
          title : 'Vue js resume constructor',
          cardLink: 'https://vue-homework-8-mark.web.app/',
          descr: 'This is a resume constructor. Here you can put together your own resume.',
          toolsMain: 'Vue js',
          toolsSecond: ['JavaScript'],
          img: require('/images/card_img/card_vue_resume.png')
        },
        {
          id: 4,
          title : 'Vue js Todos',
          cardLink: 'https://vue-ts-todos.web.app/',
          descr: 'This is a list of tasks where you can see current tasks and completed ones. You can also create a new task.',
          toolsMain: 'Vue js',
          toolsSecond: ['JavaScript'],
          img: require('/images/card_img/card_vue_todos.png')
        },
        {
          id: 5,
          title : 'Plants',
          cardLink: 'https://rolling-scopes-school.github.io/markelas-JSFEPRESCHOOL2022Q4/plants/pages/main/',
          descr: 'Website for a plant care company. The company is engaged in the cultivation, care and sale of plants. ',
          toolsMain: 'JavaScript',
          toolsSecond: ['HTML', 'CSS'],
          img: require('/images/card_img/card_plants.png')
        },
        {
          id: 6,
          title : 'Cozy House',
          cardLink: 'https://rolling-scopes-school.github.io/markelas-JSFE2022Q1/shelter/pages/main/index.html',
          descr: 'Website for shelter. They offer to give a chance to a little and nice puppy with an extremely wide and open heart. He or she will love you more than anybody else in the world.',
          toolsMain: 'JavaScript',
          toolsSecond: ['HTML', 'CSS'],
          img: require('/images/card_img/card_cozy_house.png')
        },
      ]
    }
  },
  computed:{
    toolsCheck() {
      return (this.cardsInfo.toolsSecond.length !== 1) ? this.cardsInfo.toolsSecond : this.cardsInfo.toolsSecond
    }
  }
}
</script>


<style scoped lang="scss">

</style>
