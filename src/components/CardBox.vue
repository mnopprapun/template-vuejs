<template>
<div class="card">
  <img src="img_avatar.png" alt="Avatar" style="width:100%">
  <div class="container">
    <h4><b>John Doe</b></h4> 
    <p>Architect & Engineer</p> 
  </div>
</div>
</template>

<script>
	export default {
		
	}
</script>

<style scoped>
.card {
  box-shadow: 0 4px 8px 0 rgba(255, 255, 255, 0.687);
  transition: 0.3s;
  width: 40%;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(242, 242, 242, 0.749);
}

.container {
  padding: 2px 16px;
}
</style>