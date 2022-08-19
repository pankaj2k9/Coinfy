<template>
  <section class="sec">
    <div class="container">
      <div class="box rounded">
        <span class="text-white"
          >Stejně jako Nathan, i myv Coinfy vyznáváme určité životni hodnoty.
          <br />
          Dobre vime, že nic není zadarmo,</span
        >

        <h3 class="smTitle">
          pokud chceme něčeho dosáhnout, <br />
          musíme bojovat.
        </h3>
        <p class="text-white">Proto jsme spojili sily s Nathanem.</p>
      </div>
      <!-- About With Image -->
      <div class="row">
        <div class="col-md-3">
          <img src="../../assets/about.png" alt="Razu Islam" />
        </div>
        <div class="col-md-9">
          <p class="text-color">
            Přinášíme Vám nejen možnost podilet se s námi na Nathanově <br />
            rüstu, ale i možnost vytvářet si
          </p>
          <h1 class="title">BUDOUCNOST V KRYPTOSVĚTĚ</h1>
        </div>
      </div>
      <!-- Play Store -->
      <div class="row">
        <div class="col-md-8">
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
      <!-- Card  -->
      <div class="row">
        <div class="col-md-6">
          <div class="d-flex align-items-center cardBg rounded">
            <div class="bg-content">
              <h4 class="text-white">Jen připomeneme</h4>
              <p class="text-white">
                Nathan Dzalba je mediäli hvězda, profesionálni fotbalista,
                influencer a MMA zápasnik, kterého müžete znát z řady TV reality
                show -Survivor, Kdo přežije, Love Island nebo Svatba na prvni
                pohled. Nathana jste mohli vidět napřiklad také v pěvecké
                soutěži SuperStar.
              </p>
            </div>
            <div class="position-absolute client_img">
              <img src="../../assets/client.png" alt="Client Image" />
            </div>
          </div>
        </div>
        <div class="col-md-6 bgImg rounded">
          <div class="card-content">
            <p class="text-white">
              Pokud se rozhodnete začit, <br />
              diky Nathanovi obdržite
            </p>

            <h1 class="text-white">
              bonus 20 % <br />
              7 na prvni vklad
            </h1>
            <button class="btn app_btn text-white">
              Chci se zaregistrovat
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Title from "../../components/Title/Title.vue";
export default { components: { Title } };
</script>

<style scoped>
.sec {
  padding: 5em 0px;
}
.box {
  background-color: var(--bg-color);
  padding: 2em;
}

.smTitle {
  font-size: 1.5em;
  font-weight: 600;
  color: var(--primary-color);
  margin: 0.7em 0px;
}

.text-color {
  color: var(--bg-color);
  font-weight: 500;
  margin-top: 1.2em;
}

.title {
  color: var(--primary-color);
  font-size: 1.5em;
}

.store_img {
  margin-top: 3em;
  gap: 10px;
}

.store_img img {
  width: 120px !important;
}

.row {
  margin-top: 5em;
}
.row img {
  width: 300px;
}

.cardBg {
  background-color: var(--primary-color);
  position: relative;
}

.bg-content,
.card-content {
  padding: 2em;
}

.bg-content p {
  max-width: 250px;
}

.client_img {
  top: -93px;
  right: 10px;
}

.bgImg {
  background-image: linear-gradient(#22222285, #22222293),
    url("../../assets/bg.png");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}

.app_btn {
  background-color: var(--primary-color);
  margin-top: 1em;
}
</style>
