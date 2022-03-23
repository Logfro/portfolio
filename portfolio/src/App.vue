<template>
  <div>
    <NavBar/>
    <LandingPage/>
  </div>

  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue'
import LandingPage from './components/LandingPage.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    NavBar,
    LandingPage
  }
}
</script>

<style>
@font-face {
  font-family: 'Biotif-Regular';
  src: url('./assets/fonts/Biotif-Regular.ttf');
}
@font-face {
  font-family: 'Biotif-Book';
  src: url('./assets/fonts/Biotif-Book.ttf');
}
@font-face {
  font-family: 'Biotif-Medium';
  src: url('./assets/fonts/Biotif-Medium.ttf');
}
@font-face {
  font-family: 'Biotif-SemiBold';
  src: url('./assets/fonts/Biotif-SemiBold.ttf');
}
@font-face {
  font-family: 'Biotif-Bold';
  src: url('./assets/fonts/Biotif-Bold.ttf');
}
@font-face {
  font-family: 'Biotif-MediumItalic';
  src: url('./assets/fonts/Biotif-MediumItalic.ttf');
}
@font-face {
  font-family: 'SourceCodePro-SemiBold';
  src: url('./assets/fonts/SourceCodePro-SemiBold.ttf');
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

/* UTILITIES */
* {
 margin: 0;
 padding: 0;
 box-sizing: border-box;
 background-color: #222222;
 color: #FFFFFF;
}
body {
 font-family: cursive;
}
a {
 text-decoration: none;
}
li {
 list-style: none;
}
h1  {
  font-family: "Biotif-Bold";
  font-size: 7em;
  line-height: 1;
  letter-spacing: -0.3rem;
}

h1 u {
  text-decoration: none;
  background: transparent;
  border-radius: 100px;
  height: 5px;
  box-shadow: 0 92px 0 0 #FF3D4C;
  display: block;
  width: 815px;
  margin-bottom: 135px;
}
h2 {
  font-family: "Biotif-Bold";
  font-size: 5rem;

}
h4  {
  font-family: "Biotif-SemiBold";
  background: transparent;
  font-size: 2.3rem;
  font-weight: normal;
}

sub {
  font-family: "SourceCodePro-SemiBold";
  background: transparent;
  font-size: 1.4rem;
  color: #BFC0C1;
}

    h2 mark {
        color: #FF3D4C;
    }
  h2::after {
    content: " >";
    color: #FF3D4C;
  }
</style>
