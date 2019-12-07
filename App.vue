<template>
  <div id="app">
    <nav class="navfixed"><a @click="displayHome()">Home</a><a @click="displayAbout()">About</a><a @click="displayContact()">Contact</a></nav>
    <transition name="fade" mode="out-in">
    <Home v-if="showHome"/>
    <About v-if="showAbout"/>
    <Contact v-if="showContact"/>
    </transition>
  </div>
</template>

<script>
import Home from './components/home';
import About from './components/about';
import Contact from './components/contact';

export default {
  name: 'app',
  components: {
    Home,
    About,
    Contact,
  },
  data (){
    return {
      showHome: true,
      showAbout: false,
      showContact: false,
    }
  },
  methods: {
    displayHome: function (){
      this.showHome = true,
      this.showAbout = false,
      this.showContact = false;
    },
    displayAbout: function () {
      this.showAbout = true,
      this.showHome = false,
      this.showContact = false;
    },
    displayContact: function () {
      this.showContact = true,
      this.showHome = false,
      this.showAbout = false;
    }
  }
}
</script>

<style lang="css">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 150px;
}
.fade-enter-active, .fade-leave-active {
  transition: opacity .5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active in <2.1.8 */ {
  opacity: 0;
}
.navfixed{
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  background: rgb(32,32,32);
  padding: 20px;
}
.navfixed a{
  color: white;
  margin-left: 5px;
  margin-right: 5px;
  font-size: 1.5em;
  cursor: pointer;
}
.navfixed a:hover{
  transition: text-decoration 0.25s ease-in-out, font-style 0.25s ease-in-out;
  text-decoration: underline orangered;
  font-style: italic;
}
</style>
