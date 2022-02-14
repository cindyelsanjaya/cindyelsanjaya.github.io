<template>
  <div class="header flex justify-center items-center px-16 pb-8">
    <div class="container mx-auto w-screen">
      <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 items-stretch py-5">
        <div
          v-for="left1 in left1"
          :key="left1.name"
          class="left-side flex flex-col items-start mb-5 items-center"
        >
          <img :src="left1.image" class="w-19 h-16" />
          <p class="position text-center font-semibold text-sm lg:text-xl">
            {{ left1.name }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      left1: [
        {
          image: require("../assets/image/html.svg"),
          name: "HTML",
        },
        {
          image: require("../assets/image/css.svg"),
          name: "CSS",
        },
        {
          image: require("../assets/image/less-css.svg"),
          name: "CSS LESS",
        },
        {
          image: require("../assets/image/figma.svg"),
          name: "FIGMA",
        },
        {
          image: require("../assets/image/vue.svg"),
          name: "VUE JS",
        },
        {
          image: require("../assets/image/laravel.svg"),
          name: "LARAVEL",
        },
        {
          image: require("../assets/image/mysql.svg"),
          name: "MYSQL",
        },
        {
          image: require("../assets/image/postgresql.svg"),
          name: "POSTGREESQL",
        },
        {
          image: require("../assets/image/python.svg"),
          name: "PYTHON",
        },
        {
          image: require("../assets/image/github-logo.svg"),
          name: "GITHUB",
        },
        {
          image: require("../assets/image/git.svg"),
          name: "GIT",
        },
        {
          image: require("../assets/image/firebase.svg"),
          name: "FIREBASE",
        },
        {
          image: require("../assets/image/pycharm.svg"),
          name: "PYCHARM",
        },
        {
          image: require("../assets/image/xml.svg"),
          name: "XML",
        },
        {
          image: require("../assets/image/odoo.svg"),
          name: "ODOO 11",
        },
        {
          image: require("../assets/image/adobe-xd.svg"),
          name: "ADOBE XD",
        },
        {
          image: require("../assets/image/android-studio.svg"),
          name: "ANDROID STUDIO",
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,600;1,400&family=Poppins:ital,wght@0,300;0,600;1,300&family=Roboto&display=swap");
.position {
  font-family: "Montserrat", sans-serif;
}
</style>
