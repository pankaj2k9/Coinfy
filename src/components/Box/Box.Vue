<template>
  <div class="box rounded">
    <div class="text_contentBox">
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
    <!-- Box Icon -->
    <div class="box-icon">
      <img src="../../assets/icon-bg.png" alt="Client" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.box {
  background-color: var(--bg-color);
  padding: 2em;
  margin-left: 5em;
  position: relative;
  overflow: hidden;
}

.box img {
  width: 300px;
}

.smTitle {
  font-size: 1.5em;
  font-weight: 600;
  color: var(--primary-color);
  margin: 0.7em 0px;
}

.box-icon {
  position: absolute;
  top: -30px;
  right: -76px;
}

/* responsive css */
@media (max-width: 768px) {
  .box {
    margin-left: 0px;
  }
}

</style>
