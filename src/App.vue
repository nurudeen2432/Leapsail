<template>
<div>
  <HeaderNav/>

<MainSection/>

<NextSection/>

</div>

</template>

<script>
import HeaderNav from './components/HeaderNav.vue'
import MainSection from './components/MainSection.vue'
import NextSection from './components/NextSection.vue'

export default {
  name: 'App',
  components: {
    HeaderNav,
    MainSection,
    NextSection
  }
 
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
@import './assets/bootstrap.min.css';

@import './assets/font-awesome-4.7.0/css/font-awesome.min.css';

body{
font-family: 'Source Sans Pro', sans-serif;
margin:0;
padding:0;


}
</style>
