<template>
  <div id="app">
    <Nav />
    <Banner />
    <Capability />
    <Project />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Banner from './components/Banner.vue'
import Capability from './components/Capability.vue'
import Project from './components/Project.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Nav,
    Banner,
    Capability,
    Project,
    Contact,
    Footer
  }
}
</script>
<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
#app{
  font-family: 'Poppins', sans-serif;
  font-weight: 300;
	font-size:16px;
}
</style>
