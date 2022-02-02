<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="cont">
        <div class="">
          <a class="navbar-brand" href="#">Ahmedou Yahya</a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
        </div>
      <div class="col-md-5 sections">
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">about <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#">skills</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#">portfolio</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#">contact</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
  <home></home>
  <about></about>
  <skills></skills>
  <portfolio></portfolio>
  <contact></contact>
  <Footer></Footer>
</template>

<script>
import Home from './components/Home.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    Home,
    About,
    Skills,
    Footer,
    Contact
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Yellowtail&display=swap');

.navbar{
  font-family: 'Yellowtail', cursive;  
  font-size: 50;
}
.cont{
  display: flex;

}
.navbar-brand{
  font-family: 'Yellowtail', cursive;  
  color: purple !important;
  font-size: 40px;

}
.sections{
  font-size: 25px;
}
</style>
