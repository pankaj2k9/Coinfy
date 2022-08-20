<template>
  <div class="row margin">
    <div class="col-lg-6 first">
      <div class="left rounded">
        <div class="d-flex cardBg rounded card-section">
          <div class="bg-content">
            <h4 class="text-white">Jen připomeneme</h4>
            <p class="text-white">
              Nathan Dzalba je mediäli hvězda, profesionálni fotbalista,
              influencer a MMA zápasnik, kterého müžete znát z řady TV reality
              show -Survivor, Kdo přežije, Love Island nebo Svatba na prvni
              pohled. Nathana jste mohli vidět napřiklad také v pěvecké soutěži
              SuperStar.
            </p>
          </div>
          <div class="card_img">
            <img src="../../assets/client.png" alt="Client Image" />
          </div>
        </div>
      </div>
    </div>
    <div class="col-lg-6">
      <div class="right rounded card-section">
        <div class="card-content">
          <div class="top-text">
            <p class="text-white">
              Pokud se rozhodnete začit, <br />
              diky Nathanovi obdržite
            </p>

            <h1 class="text-white">
              bonus 20 % <br />
              7 na prvni vklad
            </h1>
          </div>
          <button class="btn app_btn text-white">Chci se zaregistrovat</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
.margin {
  margin-top: 15em;
}

.card-section {
  height: 100%;
}

.card-section .bg-content {
  padding-left: 2em;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.card-section .card-content {
  padding-left: 2em;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

.left,
.right {
  background-image: url("../../assets/bg-color.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 645px;
  height: 385px;
  max-width: 100%;
  position: relative;
}

.right {
  background-image: url("../../assets/bg.png");
}

.card-content .top-text {
  margin-top: 6%;
}

.bg-content,
.card-content {
  padding-left: 2em;
}

.bg-content p {
  max-width: 250px;
}

/* .card_img {
  bottom: 0px;
  position: absolute;
  right: 10px;
} */

.card_img img {
  width: 300px;
  height: 474px;
  object-fit: cover;
  bottom: 0px;
  position: absolute;
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
  max-width: 200px;
}


@media (max-width: 1199px) {

 .left,
  .right {
    width: 100%;
    overflow: hidden;
  }
}

@media (max-width: 991px) {

 .row .first {
    margin-bottom: 4em;
  }
}
@media (max-width: 768px) {
  .margin {
    margin-top: 3em;
  }
  .row {
    margin-left: 0px;
    margin-right: 0.2em;
  }

  .row .first {
    margin-bottom: 4em;
  }
  .left,
  .right {
    width: 100%;
    overflow: hidden;
  }
  .left {
    height: auto;
  }
  .right {
    height: 430px;
  }
  .bg-content h4 {
    font-size: 24px;
    max-width: 271px;
  }
  .bg-content p {
    font-size: 18px;
    max-width: 271px;
  }
  .card_img img {
    width: 200px;
    height: 364px;
    position: relative;
    margin-bottom: 20px;
  }
  .bg-content {
    padding-left: 1em;
  }

  .card-section {
    height: 100%;
    flex-direction: column-reverse;
    align-items: center;
  }
  .card_img {
    bottom: -10px;
  }
  .card-content {
    margin-top: 2.5em;
    padding-left: 1em;
  }
  .card-content p {
    font-size: 16px;
    max-width: 260px;
  }
  .card-content h1 {
    font-size: 36px;
    max-width: 272px;
  }
  .right {
    height: auto;
  }
  .app_btn {
    margin-bottom: 20px;
  }
}

@media (max-width: 350px) {
  .app_btn {
    margin-bottom: 3em;
    display: block;
  }
}
</style>