<template>
  <div>
     <!-- Navbar -->
    <Navbar />
    
    <!-- ALl Route View -->
    <Home />

    <!-- Footer -->
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar/Navbar.vue';
import Footer from './components/Footer/Footer.vue';
import Home from './pages/Home/Home.vue';
  export default {
    components: { Navbar, Footer, Home }
}
</script>

<style>
/* Google Font */
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;1,700&display=swap');

/* Reset Css */
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none !important;
  list-style: none !important;
}
/* Variable */
:root{
  --primary-color:#63cf50;
  --text-color:#000;
  --bg-color:#702a34;
  --primary-font:'IBM Plex Sans', sans-serif;
}

h1,h2,h3,h4,h5,h6,p,a,span,button{
  font-family: var(--primary-font);
}

html, body {
  overflow-x: hidden;
}
body {
  width:100%;
}

</style>