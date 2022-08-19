<template>
  <section class="sec">
    <div class="container">
      <Box />
      <!-- About With Image -->
      <AboutImg />
      <!-- Play Store -->
      <PlayStore />

      <!-- Card  -->
      <Card />
    </div>
    <img src="../../assets/line.png" alt="Client" class="line" />
  </section>
</template>

<script>
import Title from "../../components/Title/Title.vue";
import Box from "../../components/Box/Box.vue";
import AboutImg from "../../components/AboutImg/AboutImg.vue";
import PlayStore from "../../components/PlayStore/PlayStore.vue";
import Card from "../../components/Card/Card.vue";

export default {
  components: { Title, Box, AboutImg, AboutImg, PlayStore, Card },
};
</script>

<style scoped>


.sec {
  padding: 5em 0px;
  position: relative;
}

.line {
  position: absolute;
  left: 0;
  bottom: 340px;
  width: 100vw !important;
  height: 44%;
  object-fit: cover;
  z-index: -1;
}

</style>
