<template>
  <div id="app">
    <bar-green></bar-green>
    <router-view></router-view>
    <footer-bar></footer-bar>
  </div>
</template>

<script>
import BarGreen from './components/BarGreen'
import FooterBar from './components/FooterBar'
export default {
  name: 'app',
  data () {
    return {
      modalStyle: 'modal'
    }
  },
  components: {
    BarGreen,
    FooterBar
  },
  methods: {
    showComment () {
      if (this.modalStyle === 'modal') {
        this.modalStyle = 'modal is-active'
      } else {
        this.modalStyle = 'modal'
      }
    }
  }
}

</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Kanit:300&subset=thai');
html, body {
  margin:0;
  padding:0;
  height:100%;
  background-color: #e6e6e6;
}
#app {
  font-family: 'Kanit', sans-serif;
  height: 100%;
  /*overflow: hidden;*/
}
.colornav{
  background-color: #0e8e5c !important;
  position: fixed;
  left: 0px;
  right: 0px;
  top: 0px;
  color: white;
}
.button-issue{
  background-color: #0e8e5c !important;
  position: fixed;
  right: 0px;
  bottom: 5px;
  color: white !important;
  left: 5px;
  right: 5px;
}
.coloraw{
  color: #0e8e5c !important;
}
</style>
