<template>
  <div class="home">
    <h2 @click="toAbout">homewwwww</h2>
    <img alt="Vue logo" src="../../../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
    methods:{
	    toAbout(){
	    	alert(1)
	    	window.location.href='http://localhost:8080/about.html'
        }
    },
  components: {
    HelloWorld
  }
}
</script>
