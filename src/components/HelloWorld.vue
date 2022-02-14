<template>
  <div class="header flex justify-center items-center px-16 pb-8">
    <div class="container mx-auto w-screen head">
      <div class="grid grid-cols-1 gap-8 items-center py-8">
        <div class="left-side place-content-center">
          <h3 class="position text-center font-semibold text-lg text-white">
            I’m Cindy
          </h3>
          <p
            class="position text job text-center text-base font-normal text-white"
          >
            student of Nusantara Multimedia University majoring in informatics
            2018
          </p>
        </div>
        <!-- <div class="right-side flex justify-center items-center">
          <img class="w-72 h-84" src="../assets/image/Cindy.svg" alt="" />
        </div> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,600;1,400&family=Poppins:ital,wght@0,300;0,600;1,300&family=Roboto&display=swap");
.head {
  background: linear-gradient(
    98.66deg,
    #4d0983 26.52%,
    #7f1fca 59.08%,
    #b659ff 93.47%,
    #d3d3d3 114.51%,
    #eae5ff 114.52%,
    #9446d4 114.53%,
    #b888e6 114.54%,
    #eae5ff 114.55%,
    rgba(170, 160, 210, 0.493507) 114.56%,
    #dad1ff 114.56%,
    rgba(229, 196, 255, 0.94) 114.56%
  );
  border-radius: 10px;
}
.position {
  font-family: "Montserrat", sans-serif;
}
</style>
