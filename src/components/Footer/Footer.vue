<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="footer__content">
            <div class="footer__content__logo">
              <img src="../../assets/logo.png" alt="logo" width="150" />
            </div>
            <div class="footer__content__text">
              <div class="info d-flex">
                <div class="d-flex textinfo gap-3">
                  <p>
                    Cointy je rogetorana anata spaleenot Trinity Capital LC Tato
                    spole@os oencoaná orgánem Financial Servioes Audhorty of s
                    Vincent & The Grenadiness 6biom porolon 450 L1C 2020
                  </p>
                  <p class="margin">
                    Omeznd jurisdkcec Nezakdime üity obyvatelüm urCityah
                    juatiodkci (vec USAL P ice anfonmaciai phečtito vaobecns
                    cbchadni podminky
                  </p>
                </div>

                <div class="footer_text">
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
                  <a
                    class="mt-2 d-block text-black underline"
                    href="mailto:support@coinfy.io"
                  >
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
      <div class="copyright">
        <p>CopyrightⒸ 2021-2022 Coinfy. All rights reserved.</p>
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
  padding: 3em 0px;
}

.footer__content__text {
  display: flex;
  flex-wrap: wrap;
  margin-top: 1.5em;
}

.row h3 {
  font-size: 1.2em;
}
/* .footer__content__social {
  gap: 10px;
  flex-wrap: wrap;
  margin-top: -45px;
} */
.footer__content__social a {
  text-decoration: underline !important;
  cursor: pointer;
  margin-right: 20px;
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

.info {
  width: 100%;
  justify-content: space-between;
  flex-wrap: wrap;
}

.store_img img {
  width: 70px !important;
}
.footer__social img {
  width: 20px;
  margin-right: 0.7em;
}

.info {
  display: flex;
}

.textinfo {
  /* width: 1010px; */
  flex: 1;
}

.play_store {
  margin-top: 1em;
}
.play_store h5 {
  font-size: 0.9em;
}

.footer_text {
  margin-left: 4em;
}

.copyright {
  margin-top: 2em;
}

.underline {
  text-decoration: underline !important;
}

.copyright p {
  margin-bottom: 0px !important;
}

/* .margin{
  margin-left: 1.1em;
} */

@media (max-width: 990px) {
  .textinfo {
    width: 100%;
  }
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

  .footer_text {
    margin-left: 0px;
  }
  .footer__content__social {
    flex-direction: column;
  }
}

@media (max-width: 991px) {
  .footer__content__social {
    margin-top: 0px !important;
     flex-direction: column;
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
  /* .footer__content__social {
    justify-content: center;
    align-items: center;
    flex-direction: column;
  } */
}
</style>
