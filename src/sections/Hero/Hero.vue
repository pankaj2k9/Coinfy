<template>
  <section>
    <div class="container">
      <div class="flex-row d-md-flex justify-content-start align-items-center">
        <div class="hero_content">
          <Title title="A je to tady!" />
          <h1>Nathan Szaba a Coinfy <br> spojuji sily</h1>
          <p class="text-color">Do baje jdeme spolecne     - s cilem zazarit!</p>
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
  <!-- Overlay -->
  <div class="position-fixed top-0 bottom-0 overlay"></div>
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
.overlay {
    width: 100%;
    height: 100%;
    background: #f74c4c70;
    pointer-events: none;
    z-index: 100;
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


/* Media COde */
@media (max-width:550px){

  .hero_content{
    margin-top: 3em;
  }
  .hero_content h1{
      font-weight: 400;
      font-size: 36px;
      max-width: 272px;
  }
  .hero_content p{
      font-size: 18px;
      color: #707070;
      max-width: 204px;
  }
}

</style>
