<template>
  <div class="header flex justify-center items-center px-16 pb-8">
    <div class="container mx-auto w-screen">
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-stretch py-5">
        <div
          v-for="job in job"
          :key="job.date"
          class="left-side place-content-center py-5 rounded-lg drop-shadow-xl border"
        >
          <h3
            class="position purple text-center font-semibold text-lg lg:text-xl lg:text-2xl"
          >
            {{ job.date }}
          </h3>
          <p
            class="position text-center tesxt-sm lg:text-base font-semibold pl-2"
          >
            {{ job.position }}
          </p>
          <p
            class="position text-left text-sm lg:text-base font-light pl-2 py-2"
          >
            {{ job.description }}
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
      job: [
        {
          date: "JANUARY 2021 - MAY 2021",
          position: "Assistent Laboratory Computer Network",
          description:
            " Assisting lecturers in teaching Computer Network practicum courses(Wireshark, GNS3, CPT).",
        },
        {
          date: "JANUARY 2021 - MAY 2021",
          position: "Assistent Laboratory Web Programming",
          description:
            "Assisting lecturers in teaching Web Programming practicum courses(Codeigniter, PHP, Mysql).",
        },
        {
          date: "SEPTEMBER 2019 - DECEMBER 2019",
          position: "Mentoring 2019",
          description:
            "Mentoring is one of the big events at Multimedia Nusantara University which is specially for new students. In this event, I act as a Mentor, where I will teach the 5C values taught by Kompas Gramedia, namely: caring, credible, competence, competitive, and customer delight.",
        },
        {
          date: "SEPTEMBER 2020 - DECEMBER 2020",
          position: "CSIC 2020",
          description:
            "CSIC is an event of the Informatics Association. Here I act as Visual Coordinator where I am responsible for all Instagram designs, certificates and virtual backgrounds.",
        },
        {
          date: "OCTOBER 2020 - NOVEMBER 2020",
          position: "Webinar STARTUP by PT. Cahaya Bangsa",
          description:
            "This webinar provides a seminar on start-ups in the millennial era and here I act as an admin who will be responsible for all attendance of the participants.",
        },
        {
          date: "JUNE 2021 - DECEMBER 2021",
          position:
            "Software Engineer Intern at Human Resource Information System(HRIS) Kompas Gramedia",
          description:
            "Assist the software engineer team in developing the Kompas Gramedia HR digital system.",
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
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.purple {
  color: #7f1fca;
}
</style>
