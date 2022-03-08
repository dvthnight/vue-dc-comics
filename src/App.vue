
<template>
  <div id="app">
    <DcHeader/>
    <DcMain/>
    <DcFooter/>

  </div>
</template>

<script>
import DcHeader from './components/DcHeader.vue'
import DcMain from "./components/DcMain.vue"
import DcFooter from "./components/DcFooter.vue"

export default {
  name: 'App',
  components: {
    DcHeader,
    DcMain,
    DcFooter,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;

   
 
}

 *{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }
</style>
