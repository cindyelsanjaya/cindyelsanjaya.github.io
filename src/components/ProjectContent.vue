<template>
  <div class="header flex justify-center items-center px-16 pb-8">
    <div class="container mx-auto w-screen">
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-stretch py-5">
        <div
          v-for="project in project"
          :key="project.title"
          class="left-side items-stretch place-content-center py-5 rounded-lg drop-shadow-xl border"
        >
          <h3
            class="position purple text-center font-semibold text-lg lg:text-2xl"
          >
            {{ project.title }}
          </h3>
          <p
            class="position text-left text-sm lg:text-base font-light pl-2 py-8"
          >
            {{ project.desc }}
          </p>
          <div class="grid grid-cols-2 lg:grid-cols-4 gap-8 items-stretch py-5">
            <div class="flex flex-col items-start mb-5 items-center">
              <img class="w-19 h-16" :src="project.image1" />
              <p
                class="position text-center font-semibold text-sm lg:text-base"
              >
                {{ project.title1 }}
              </p>
            </div>
            <div class="flex flex-col items-start mb-5 items-center">
              <img class="w-19 h-16" :src="project.image2" />
              <p
                class="position text-center font-semibold text-sm lg:text-base"
              >
                {{ project.title2 }}
              </p>
            </div>
            <div class="flex flex-col items-start mb-5 items-center">
              <img class="w-19 h-16" :src="project.image3" />
              <p
                class="position text-center font-semibold text-sm lg:text-base"
              >
                {{ project.title3 }}
              </p>
            </div>
            <div class="flex flex-col items-start mb-5 items-center">
              <img class="w-19 h-16" :src="project.image4" />
              <p
                class="position text-center font-semibold text-sm lg:text-base"
              >
                {{ project.title4 }}
              </p>
            </div>
          </div>

          <div class="flex items-stretch justify-center py-5">
            <a
              class="btn text-white font-bold py-2 px-4 border-b-4 rounded"
              :href="project.link"
              >SEE THIS PROJECT</a
            >
          </div>
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
      project: [
        {
          title: "MUSIC PLAYER",
          desc: "Android-based music player application using Java and XML languages.",
          image1: require("../assets/image/android-studio.svg"),
          title1: "ANDROID STUDIO",
          image2: require("../assets/image/xml.svg"),
          title2: "XML",
          image3: require("../assets/image/java.svg"),
          title3: "JAVA",
          link: "https://github.com/ciel9/V-Player",
        },
        {
          title: "MEDICAL CHATBOT",
          desc: "is a chat bot application is named hela, where it can tell the user by the way the user answers a choice of questions about what the user feels. This application is created using the regular PHP language.",
          image1: require("../assets/image/php.svg"),
          image2: require("../assets/image/html.svg"),
          image3: require("../assets/image/css.svg"),
          title1: "PHP",
          title2: "HTML",
          title3: "CSS",
          link: "https://github.com/ciel9/Medical-Chat-Bot",
        },
        {
          title: "GAME MAZE BALL",
          desc: "A game where the player is a ball that must collect points in the form of a crystall worth 10 points and if you find gate exit of the maze, you will get a large crystall has a point value of 100. In the maze,there is some obstacle nail too. Here I made the Easy Maze section and Navigation menus and sound buttons.",
          image1: require("../assets/image/unity.svg"),
          image2: require("../assets/image/c.svg"),
          title1: "UNITY",
          title2: "C++",
          link: "https://github.com/ciel9/Game-Maze-Ball",
        },
        {
          title: "ECOMMERCE WEB",
          desc: "is an e-commerce website. Where he sells car and motorcycle care products also serves several home service. To order home service, a scheduling will be made before the customer contacts the seller. Here I created it using vuejs, javascript, html, and css.",
          image1: require("../assets/image/vue.svg"),
          image2: require("../assets/image/html.svg"),
          image3: require("../assets/image/css.svg"),
          image4: require("../assets/image/javascript.svg"),
          title1: "VUE JS",
          title2: "HTML",
          title3: "CSS",
          title4: "JAVASCRIPT",
          link: "https://github.com/ciel9/Website-Ecommerce-FrontEnd",
        },
        {
          title: "USHOP",
          desc: "is an ecommerce website using laravel framework. Here I created a discount feature, cart and also an admin page.",
          image1: require("../assets/image/laravel.svg"),
          image2: require("../assets/image/html.svg"),
          image3: require("../assets/image/css.svg"),
          title1: "LARAVEL",
          title2: "HTML",
          title3: "CSS",
          link: "https://github.com/ciel9/UShop-Laravel",
        },
        {
          title: "UMN CANTEEN WEB",
          desc: "UMN Canteen Website Design Interface using Adobe XD.",
          image1: require("../assets/image/adobe-xd.svg"),
          link: "https://github.com/ciel9/Design-Interface-Website-Kantin-UMN",
          title1: "ADOBE XD",
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
.left-side {
  background: #f1f1f2;
  border: 4px solid #eae5ff;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 4px;
}
.purple {
  color: #7f1fca;
}
.btn {
  background: #7f1fca;
  border-bottom: solid 5px #957bff;
}
.btn:hover {
  background: #957bff;
  border-bottom: solid 5px #7f1fca;
}
</style>
