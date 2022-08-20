<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-10">
          <div class="footer__content">
            <div class="footer__content__logo">
              <img src="../../assets/logo.png" alt="logo" width="150" />
            </div>
            <div class="footer__content__text">
              <div class="info d-flex gap-0">
                <div class="d-flex textinfo">
                  <p>
                    Cointy je rogetorana anata spaleenot Trinity Capital LC Tato
                    spole@os oencoaná orgánem Financial Servioes Audhorty of s
                    Vincent & The Grenadiness 6biom porolon 450 L1C 2020
                  </p>
                  <p>
                    Omeznd jurisdkcec Nezakdime üity obyvatelüm urCityah
                    juatiodkci (vec USAL P ice anfonmaciai phečtito vaobecns
                    cbchadni podminky
                  </p>
                </div>

                <div>
                  <h3>Sociální odkazy</h3>

                  <div class="footer__social">
                    <a href="https://www.facebook.com/">
                      <img src="../../assets/facebook.png" alt="facebook" />
                    </a>
                    <a href="https://www.instagram.com/">
                      <img src="../../assets/instagram.png" alt="instagram" />
                    </a>
                    <a href="https://twitter.com/">
                      <img src="../../assets/twitter.png" alt="twitter" />
                    </a>
                    <a href="https://www.youtube.com/">
                      <img src="../../assets/youtube.png" alt="youtube" />
                    </a>
                  </div>
                  <!-- Play Store -->
                  <div class="play_store">
                    <h5>Ziskat DXtrade Mobile</h5>
                    <div class="store_img d-flex">
                      <img src="../../assets/app.png" alt="Client" />
                      <img src="../../assets/play.png" alt="Client" />
                    </div>
                  </div>
                  <a class="mt-2 d-block" href="mailto:support@coinfy.io">
                    <img src="../../assets/sm-logo.png" alt="Client" />
                    support@coinfy.io
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex footer__content__social">
        <a>VSeobeond olohodnl podmik</a>
        <p>ohrana 0sobnich üdaj</p>
      </div>
      <!-- Copy Right text -->
      <div>
        <p>Copyright 2021 2022 Colsy All nghts resarvwd.</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  background-color: #f3f3f3;
  padding: 5em 0px;
}

.footer__content__text {
  display: flex;
  flex-wrap: wrap;
  margin-top: 1.5em;
}

.row h3 {
  font-size: 1.2em;
}
.footer__content__social {
  gap: 10px;
  flex-wrap: wrap;
}
.footer__content__social a {
  text-decoration: underline !important;
  cursor: pointer;
}
.footer__content__text p:first-child {
  width: 50%;
}
.footer__content__text p:last-child {
  width: 50%;
}

.store_img {
  gap: 10px;
  justify-content: center;
  align-items: center;
}

.store_img img {
  width: 70px !important;
}
.footer__social img {
  width: 20px;
  margin-right: 0.7em;
}

.play_store {
  margin-top: 1em;
}
.play_store h5 {
  font-size: 0.9em;
}

@media (max-width: 768px) {
  .row {
    display: flex;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
  }

  .textinfo {
    flex-direction: column;
  }

  .info {
    flex-direction: column-reverse;
  }

  .info p {
    width: 100% !important;
  }
}

@media (max-width: 550px) {
  .footer .container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin: 0 auto;
    text-align: center;
  }

  .textinfo {
    margin-top: 3em;
  }
  .footer__content__social {
    justify-content: center;
    align-items: center;
  }
}
</style>
