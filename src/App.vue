<template>
  <div id="app">
    {{massage}}
    <zheXian></zheXian>
<div id="charts1"></div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import zheXian from './components/zheXian.vue'


  export default {
    components:{
    HelloWorld,
      zheXian,

    },
  name: 'App',
  data(){
    return{
      massage:'hello world',

    }
  },

    methods:{

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
