<template>
  <div class="home">
    <HelloWorld />
    <About />
    <ExperienceTitle />
    <ExperienceContent />
    <SkillTitle />
    <Skill />
    <ProjectTitle />
    <ProjectContent />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import About from "@/components/About.vue";
import ExperienceTitle from "@/components/ExperienceTitle.vue";
import ExperienceContent from "@/components/ExperienceContent.vue";
import SkillTitle from "@/components/SkillTitle.vue";
import Skill from "@/components/Skill.vue";
import ProjectTitle from "@/components/ProjectTitle.vue";
import ProjectContent from "@/components/ProjectContent.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    HelloWorld,
    About,
    ExperienceTitle,
    ExperienceContent,
    SkillTitle,
    Skill,
    ProjectTitle,
    ProjectContent,
    Footer,
  },
};
</script>
