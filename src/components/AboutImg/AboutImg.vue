<template>
   <div class="row image_sec align-items-center">
        <div class="col-md-4">
          <img src="../../assets/about.png" alt="Razu Islam" />
        </div>
        <div class="col-md-6">
          <p class="text-color">
            Přinášíme Vám nejen možnost podilet se s námi na Nathanově <br />
            rüstu, ale i možnost vytvářet si
          </p>
          <h1 class="title">BUDOUCNOST V KRYPTOSVĚTĚ</h1>
        </div>
      </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.row {
  margin-top: 5em;
}

.image_sec {
  margin-left: 5em;
}

.image_sec img {
  width: 100%;
}

.title {
  color: var(--primary-color);
  font-size: 1.5em;
}
.text-color {
  color: var(--bg-color);
  font-weight: 500;
  margin-top: 1.2em;
}

@media (max-width: 768px) {

  .row{
    flex-direction: column-reverse !important;
  }
  .image_sec {
    margin-left: 0;
  }
  .image_sec p{
    font-size: 18px;
    max-width: 272px;
  }
  .title{
    font-size: 32px;
    max-width: 272px;
  }
}


</style>