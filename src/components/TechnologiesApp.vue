<template>
  <section class="technologies" id="skills">
    <div class="technologies__container">
      <div class="technologies page-parts">
        <h4 class="technologies page-parts__text">👨‍💻 Skills</h4>
      </div>
      <h2 class="technologies__title">Technologies and skills</h2>
      <div class="technologies__block">
        <img
            v-for="img in imgLinks"
           :key="img.id"
           :src="img.srcImg"
           :alt="img.altImg"
           class="technologies__block__icon"
        >
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TechnologiesApp",
  data() {
    return {
      imgLinks : [
        { srcImg: require('/icons/Javascript.svg'),
          altImg: 'Javascript',
          id: 1
        },
        { srcImg: require('/icons/TypeScript.svg'),
          altImg: 'TypeScript',
          id: 2
        },
        { srcImg: require('/icons/Vue.svg'),
          altImg: 'Vue',
          id: 3
        },
        { srcImg: require('/icons/vuex-store.svg'),
          altImg: 'vuex',
          id: 4
        },
        { srcImg: require('/icons/vuetify.svg'),
          altImg: 'vuetify',
          id: 5
        },
        { srcImg: require('/icons/css.svg'),
          altImg: 'css',
          id: 6
        },
        { srcImg: require('/icons/sass.svg'),
          altImg: 'sass',
          id: 7
        },
        { srcImg: require('/icons/html.svg'),
          altImg: 'HTML',
          id: 8
        },
        { srcImg: require('/icons/bootstrap-4.svg'),
          altImg: 'Bootstrap',
          id: 9
        },
        { srcImg: require('/icons/Github_tech.svg'),
          altImg: 'Github',
          id: 10
        },
        { srcImg: require('/icons/git.svg'),
          altImg: 'Git',
          id: 11
        },
        { srcImg: require('/icons/Figma.svg'),
          altImg: 'Figma',
          id: 12
        },
        { srcImg: require('/icons/Insomnia.svg'),
          altImg: 'Insomnia',
          id: 13
        },
        { srcImg: require('/icons/Nodejs.svg'),
          altImg: 'Nodejs',
          id: 14
        },
      ]
    }
  }
}
</script>

<style scoped lang="scss">

</style>
