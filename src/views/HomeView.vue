<template>
  <section class="home-section" id="home" v-motion-fade>
    <div class="container">
      <h4 class="section-heading">Hello!</h4>
      <IntroAnimation />
      <p class="section-text">
        My name is Elsa, I'm a Full-stack Developer who is very passionated and
        quick learner.<br />
        I am working on web interfaces that should be good looking, simple and
        enjoyable to use.<br />
        If you are interested in cooperation and transforming your ideas into a
        great projects, please contact me in any way convenient for you.
      </p>
    </div>
  </section>
</template>

<script>
import IntroAnimation from "@/components/IntroAnimation.vue";

export default {
  name: "HomeView",
  components: {
    IntroAnimation,
  },
};
</script>

<style>
.home-section .section-heading {
  color: var(--blue);
}
.section-text {
  color: rgb(16, 173, 11);
}
</style>
