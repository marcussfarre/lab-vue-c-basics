<script setup>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';
  import ExerciceOne from './components/ExerciseOne.vue';
  import ExerciseTwo from './components/ExerciseTwo.vue';
  import ExerciseThree from './components/ExerciseThree.vue';

</script>

<template>
  <Navbar />
  <ExerciceOne />
  <hr>
  <ExerciseTwo />
  <hr>
  <ExerciseThree />
  <Footer />
</template>

<style scoped>
  .containerOne {
    margin: 2% 5%;
  }
  .containerTwo {
    margin: 2% 5%;
  }
</style>
