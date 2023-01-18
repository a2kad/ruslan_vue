<template>
  <div class="container">
	<main class="main">
		Main Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore totam repellat quia nesciunt non, saepe praesentium necessitatibus repudiandae sed molestias accusamus natus nulla? Eveniet repudiandae recusandae expedita esse porro neque.
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Autem, exercitationem nam quasi, odit quaerat ex dolorum recusandae, voluptates aliquid voluptas sapiente. Qui velit quas animi dicta reprehenderit aspernatur vero suscipit?
		Lorem ipsum dolor sit amet, consectetur adipisicing elit. Explicabo distinctio esse at veniam, iusto velit enim est corporis necessitatibus voluptas ea quis magnam aliquam, aperiam illo cum voluptatum perspiciatis fuga!
	</main>
	<aside class="aside">
		Aside Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus quod suscipit odit adipisci nemo architecto ratione eius, aperiam mollitia aliquid! Praesentium quos consectetur delectus placeat dicta harum iure, officia est.
	</aside>
  </div>
</template>

<script>

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&display=swap');
#app {
	font-family: 'Montserrat', sans-serif;
}
body {
	margin: 0;
}
.container {
	display: flex;
	flex-wrap: wrap;
	align-items: stretch;
}
.aside{
	background-color: darkcyan;
}
.aside, .main {
	width: 100%;
	min-height: 1px;
}
@media (min-width: 990px) {
	.aside {
		flex: 0 0 33.333333%;
		max-width: 33.333333%;
		order: 1;
	}
	.main {
		flex: 0 0 66.666667%;
		max-width: 66.666667%;
		order: 2;
	}
}
@media (min-width: 1400px) {
	.aside {
		flex: 0 0 25%;
		max-width: 25%;
		order: 1;
	}
	.main {
		flex: 0 0 75%;
		max-width: 75%;
		order: 2;
	}
}


</style>
