<template>
  <div class="block">
	<div class="list">
		<div class="left__column">
			left
		</div>
		<div class="right__column">right</div>
	</div>
  </div>
</template>

<script>

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&display=swap');
#app {
	font-family: 'Montserrat', sans-serif;
	margin: 0;
	padding: 0;
}

div .block{
	display: flex;
	
	justify-content: center;
}
div .list{
	border: 1px solid rgb(224, 224, 224);
	width: 90%;
	box-shadow: -6px 6px 10px 1px rgba(51,51,51,0.5);
}

</style>
