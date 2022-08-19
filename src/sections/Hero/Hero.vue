<template>
  <section>
    <div class="container">
      <div class="flex-row d-md-flex justify-content-start align-items-center">
        <div class="hero_content">
          <Title title="A je to tady!" />
          <h1>Nathan Szaba a Coinfy <br> spojuji sily</h1>
          <p class="text-color">Do baje jdeme spolecne- s cilem zazarit!</p>
        </div>
        <div class="hero-img">
            <img
              src="../../assets/hero.png"
              alt="Hero"
              class="img-fluid"
              lazy="loading"
            />
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
  max-width: 500px;
}

.hero_content h1{
    font-weight: 700;
}

.hero-img {
  width: 65%;
}

@media (max-width: 991px) {
  .hero-img {
    width: 100%;
  }
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

</style>
