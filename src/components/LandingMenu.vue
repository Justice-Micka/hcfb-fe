<template>
  <div id="app">
    <div class="d-flex justify-content-center" style="margin-top: 3em; margin-bottom: 2em;">
      <h1>[feed]</h1>
    </div>
    <div class="d-flex justify-content-center">
      <button type="button" class="btn btn-menu"><i class="fas fa-apple-alt" style="font-size: 8em; color: #EE0055">
      </i><br><br>
      Food Rescue</button>
      <button  type="button" class="btn btn-menu weight"><i class="fas fa-weight" style="font-size: 8em; color: #7DB1B1">
      </i><br><br>
      Warehouse Entry </button>
    </div>
    <div class="d-flex justify-content-center">
      <button  type="button" class="btn btn-menu"><i class="fas fa-truck" style="font-size: 8em; color: #0e6502">
      </i><br><br>
      Distribution </button>
      <button  type="button" class="btn btn-menu"><i class="fas fa-tools" style="font-size: 8em; color: #2c33CC">
      </i><br><br>
      Admin </button>
    </div>      
  </div>
</template>

<script>
export default {
  name: 'LandingMenu',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
    background-color: #282c34;
}

h1 {
	font-family: 'Open Sans', serif;
	font-size: 6em;
	color: white;
} 

.btn-menu {
	margin-left: 2rem;
	margin-right: 2rem;
	width: 15rem;
	height: 15rem;
	margin-top: 1rem;
	margin-bottom: 1rem;
	font-family: 'Open Sans', sans-serif;
	font-weight: bold;
	color: #ffffff;
}
.weight {
  background:url("/Users/michaelrwalker/Documents/GitHub/hcfb-fe/src/assets");
}
</style>
