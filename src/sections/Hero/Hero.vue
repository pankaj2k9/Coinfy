<template>
    <section>
        <div class="container">
            <div class="d-flex justify-content-start align-items-center">
                <div class="hero_content">
                    <Title title="A je to tady!" />
                    <h1>Nathan Szaba a Coinfy spojuji sily</h1>
                    <p>Do baje jdeme spolecne- s cilem zazarit!</p>
                </div>
                <div class="position-relative">
                    <img src="../../assets/hero.png" alt="Hero" class="img-fluid" width="450" />
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import Title from '../../components/Title/Title.vue';
    export default {
    components: { Title }
}
</script>

<style scoped>
.hero_content{
    max-width: 500px;
}
</style>