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
              <p>
                Cointy je rogetorana anata spaleenot Trinity Capital LC Tato
                spole@os oencoaná orgánem Financial Servioes Audhorty of s
                Vincent & The Grenadiness 6biom porolon 450 L1C 2020
              </p>
              <p>
                Omeznd jurisdkcec Nezakdime üity obyvatelüm urCityah juatiodkci
                (vec USAL P ice anfonmaciai phečtito vaobecns cbchadni podminky
              </p>
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
        </div>
        <div class="col-md-2">
          <h3>Sociální odkazy</h3>
          
        </div>
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

.footer__content__text{
    display: flex;
    flex-wrap: wrap;
    margin-top: 1.5em;
}

.footer__content__social{
    gap: 10px;
}
.footer__content__social a{
    text-decoration: underline !important;
    cursor: pointer;
}
.footer__content__text p:first-child{
    width: 50%;
}
.footer__content__text p:last-child{
    width: 50%;
}
</style>
