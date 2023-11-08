<template>
  <section class="recommend" id="recommendation">
    <div class="recommend__container">
      <div class="recommend page-parts">
        <h4 class="recommend page-parts__text">💬 Recommend</h4>
      </div>
      <h2 class="recommend__title">Recommended by managers</h2>
      <div class="recommend__box">
        <div class="recommend__box__card" v-for="card in recomCard" :key="card.id">
          <img :src="card.companyLogo" :alt="card.altCompanyLogo" class="card__company-logo">
          <div class="card__body">
            <img src="../../icons/user_logo.svg" alt="card photo" class="card__photo">
            <div class="card__person">
              <h4 class="card__person__name">{{card.personName}}</h4>
              <p class="card__person__position">{{card.personPosition}}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "RecommendApp",
  data() {
    return {
      recomCard: [
        {
          id: 1,
          companyLogo: require('/icons/tinkoff.svg'),
          altCompanyLogo: 'Tinkoff logo',
          personName: 'Sergey Usenko',
          personPosition: 'Teamlead'
        },
        {
          id: 2,
          companyLogo: require('/icons/_.png'),
          altCompanyLogo: 'Comngo logo',
          personName: 'Alexander Shaikevich',
          personPosition: 'CEO'
        },
        {
          id: 3,
          companyLogo: require('/icons/_.png'),
          altCompanyLogo: 'Comngo logo',
          personName: 'Mansur Zakirov',
          personPosition: 'Teamlead'
        },
      ]
    }
  },
  computed:{
    windowSizeCheck() { //Показываем карусель при маленьких разрешениях
      return window.innerWidth >= 1020;
    }
  }
}
</script>

<style scoped>

</style>
