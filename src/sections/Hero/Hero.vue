<template>
  <section>
    <div class="container">
      <div class="flex-row d-md-flex justify-content-start align-items-center">
        <div class="hero_content">
          <Title title="A je to tady!" />
          <h1>Nathan Szaba a Coinfy <br> spojuji sily</h1>
          <p class="text-color">Do baje jdeme spolecne- s cilem zazarit!</p>
        </div>
        <div class="position-relative left">
            <img
              src="../../assets/hero.png"
              alt="Hero"
              class="img-fluid"
            />
            <div class="inner-img">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
            <div class="inner-img-2">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
            <div class="inner-img-3">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
            <div class="inner-img-4">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
            <div class="inner-img-5">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
            <div class="inner-img-6">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
            <div class="inner-img-7">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
            <div class="inner-img-8">
                <img src="../../assets/1.png" alt="Razu islam">
            </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Title from "../../components/Title/Title.vue";
export default {
  components: { Title },
};
</script>

<style scoped>
.hero_content {
  max-width: 700px;
}

.container img{
    width: 100%;
}

.left{
    width: 550px;
}

.text-color {
  color: var(--bg-color);
  font-weight: 500;
  margin-top: 1.2em;
}

.inner-img {
    position: absolute;
    top: 30px;
}
.inner-img-2 {
    position: absolute;
    top: 50px;
}
.inner-img-3 {
    position: absolute;
    top: 70px;
}
.inner-img-4 {
    position: absolute;
    top: 100px;
}
.inner-img-5 {
    position: absolute;
    top: 120px;
}
.inner-img-6 {
    position: absolute;
    top: 140px;
}
.inner-img-7 {
    position: absolute;
    top: 160px;
}
.inner-img-8 {
    position: absolute;
    top: 180px;
}

</style>
