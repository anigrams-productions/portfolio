<template>
  <div class="home text-center">
    <h1 class="sr-only">Cera White's Game Design Portfolio</h1>

    <div class="container-fluid bg-light pt-5 pb-5">
      <div class="d-flex flex-column justify-content-center align-items-center">
        <img class="d-block" alt="Cera, the Game Knight" src="../assets/Cera-Icon.png">
        <h2 class="introduction mt-2">
          Hi! I'm <span class="font-weight-bold text-success">Cera White</span>,<br />
          <strong>game designer</strong> and <strong>programmer</strong>.
        </h2>
      </div>
    </div>

    <about class="d-none d-md-block"></about>

    <skills></skills>

    <projects></projects>

    <contact></contact>
  </div>
</template>

<script>
import About from '@/components/About.vue';
import Skills from '@/components/Skills.vue';
import Projects from '@/components/Projects.vue';
import Contact from '@/components/Contact.vue';

export default {
  name: 'Home',
  components: {
    About,
    Skills,
    Projects,
    Contact,
  },
};
</script>

<style lang="scss" scoped>

</style>
