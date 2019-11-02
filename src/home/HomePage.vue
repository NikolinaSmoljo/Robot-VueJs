<template>
<div class="home">
  <div>
    <h1>Vue.js exercise - Robot</h1>
    {{ msg }}
    <img class="robot" src="../assets/robot-home.png" aria-hidden="true" />
  </div>
  <div class="get-started">
    <a href="">Get started</a> building your first robot!
  </div>
</div>
</template>

<script>
export default {
	name: 'MojPrviZadatak',
	props: {
		msg: String
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  text-align: center;
}
.robot {
  height: 300px;
}
.get-started {
  padding-top: 20px;
  font-size: 25px;
}
h1 {
  text-align: center;
  color:orangered;
  font-size: 16px;
} 
</style>