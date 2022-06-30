<template>
  <div id="app" style="margin-top: -25px;">
    <NavbarVue />
    <div style="padding: 10px;"> 
   <HeroNew />
    <Intro />
    <tableContents />
    <Education />
    <ProjectsVue />
    <DesignVue />
    <ContactVue />
   
    </div>
  </div>
</template>

<script>

import HeroNew from './components/HeroNew.vue'
import Intro from './components/Intro.vue'
import tableContents from './components/tableContents.vue'
import Education from './components/Education.vue'
import ProjectsVue from './components/Projects.vue'
import DesignVue from './components/Design.vue'
import ContactVue from './components/Contact.vue'
import NavbarVue from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    NavbarVue,
ProjectsVue,
  HeroNew,
    Intro,
    tableContents,
    Education,
    DesignVue,
    ContactVue
  }
}
</script>

<style>
#app {
  font-family: Helvetica;
  color: white;
}

 @media only screen and (max-width: 390px) {
    .body {
        text-align: center;
    }

    .paragraph2 {
        text-align: center;
    }

    .pickaz{
      width: 50%;
    }


    
}

@font-face {
  font-family: "Helvetica";
  src: url('./assets/Helvetica.ttf');
}

@font-face {
  font-family: "Happy Time";
  src: url('./assets/HappyTime.otf');
}

</style>
