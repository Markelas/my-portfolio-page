<template>
  <section class="about-me" id="aboutMe">
    <div class="about-me__container">
      <div class="about-me__photo">
        <img src="../../images/ProfilePic.png" alt="photo" class="photo__my-photo">
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
          <p class="about-me__info__descr__text__small"> Education: Kazan National Research Technical University
            named after A. N. Tupolev - KAI, Kazan. On specialty Information Systems and Technologies.
            <br>I have been developing and programming interfaces for more than 2 years. Currently I use JavaScript, Typescript, Vue JS, Vuex, Vue Router, Vuetify, SCSS, Git.
            <br>I try every day to be a little better than yesterday. In my spare time I like to paint and go to the GYM.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>

</script>

<style scoped>
.about-me__info__descr__text__small{
  display: none;
  font-size: 16px;
  color: rgb(173, 173, 173);
  line-height: 160%;
  text-align: justify;
}
@media (max-width: 890px) {
  .about-me__info__descr__text{
    display: none;
  }
  .about-me__info__descr__text__small{
    display: inherit;
  }
  .about-me__container{
    padding-bottom: 10px;
  }
}
</style>
