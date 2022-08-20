<template>
    <div class="row gap-4 gap-md-4 margin">
        <div class="left rounded">
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
            <div class="card_img">
              <img src="../../assets/client.png" alt="Client Image" />
            </div>
          </div>
        </div>
        <div class="right rounded">
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
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>

.margin{
  margin-top: 15em;
}

.left,
.right {
  background-image: url("../../assets/bg-color.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 645px;
  height: 385px;
  position: relative;
}

.right {
  background-image: url("../../assets/bg.png");
}

.bg-content,
.card-content {
  margin-top: 4.5em;
  padding-left: 2em;
}

.bg-content p {
  max-width: 250px;
}

.card_img {
  bottom: 0px;
  position: absolute;
  right: 10px;
}

.card_img img {
  width: 300px;
  height: 474px;
  object-fit: cover;
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

@media (max-width: 768px) {
  .row {
    margin-left: 0px;
    margin-right: 0.2em;
  }

  .left,
  .right {
    width: 100%;
  }

  .card_img {
    display: none;
  }
}

</style>