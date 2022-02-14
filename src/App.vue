<template>
  <div class="">
    <nav
      class="container px-6 py-8 mx-auto md:flex md:justify-between md:items-center"
    >
      <div class="flex items-center justify-between">
        <router-link
          to="/"
          class="text-logo text-xl font-bold md:text-2xl hover:text-indigo-400"
          >Cv Cindy
        </router-link>
      </div>
    </nav>
  </div>
  <router-view />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,600;1,400&family=Poppins:ital,wght@0,300;0,600;1,300&family=Roboto&family=Sacramento&display=swap");
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.route {
  font-family: "Poppins", "sans-serif";
  color: #424141;
}
.route:hover {
  color: #7f1fca;
}
.text-logo {
  font-family: "Sacramento", "sans-serif";
  color: #7f1fca;
}
</style>
