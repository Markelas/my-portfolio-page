<template>
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
            <a href="https://t.me/Marlontis" class="mail__telegram">Text in Telegram<img src="../../icons/PaperPlaneTilt.svg" alt="Paper Plane icon"></a>
          </div>
          <p class="mail__text">E-mail:</p>
          <a href= "mailto:markgirfanov@gmail.com" class="mail__adress">markgirfanov@gmail.com</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContactsApp"
}
</script>


<style scoped lang="scss">

</style>
