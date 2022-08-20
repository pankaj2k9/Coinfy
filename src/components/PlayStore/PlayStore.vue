<template>
    <div
        class="row gap-4 gap-md-0 align-items-center position-relative play_store"
      >
        <div class="col-md-7">
          <Title title="Jsme Coinfy" />
          <p class="text-color">
            S námi müžete obchodovat kryptoměny jednoduše a odkudkoli,
            <br />
            diky platformě DXtrade.
          </p>
          <p class="text-color">
            Müžete obchodovat na nárüst trhu, ale i vydělávat, pokud trhy
            klesaji.
          </p>
          <div class="store_img d-flex">
            <img src="../../assets/app.png" alt="Client" />
            <img src="../../assets/play.png" alt="Client" />
          </div>
        </div>

        <div class="col-md-4">
          <img src="../../assets/mobile.png" alt="Client Images" />
        </div>
      </div>
</template>

<script>
import Title from '../Title/Title.vue';
    export default {
    components: { Title }
}
</script>

<style scoped>

.play_store{
  margin-top: 5em;
}
.play_store img {
  width: 350px;
  max-width: 100%;
}

.store_img img {
  width: 120px !important;
}

.store_img {
  margin-top: 3em;
  gap: 10px;
}

.text-color {
  color: var(--bg-color);
  font-weight: 500;
  margin-top: 1.2em;
}

@media (max-width:550px){

  .play_store p{
    font-size: 18px;
  }
}

</style>