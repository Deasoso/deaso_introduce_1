<template>
  <div id="app">
    <Header />
      <!-- <div class="leftback" />
      <div class=" rightback" /> -->
      <router-view />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";

export default {
  name: 'app',
  components: {
    Header,
    Footer
  },
  data: () => {
     return {

     }
  },
  methods: {
    
  },
  mounted() {

  }
}
</script>

<style>
.leftback{
  position: fixed;
  left: 0;
  top: 0;
  width: calc(50vw - 640px);
  height: 100vh;
  background-color:rgba(0, 0, 0, 0.562)
}
.rightback{
  position: fixed;
  right: 0;
  top: 0;
  width: calc(50vw - 640px);
  height: 100vh;
  background-color:rgba(0, 0, 0, 0.562)
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
  text-align: center;
  color: #2c3e50;
}
</style>
