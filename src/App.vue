<script setup lang="ts">
  import { RouterLink, RouterView } from 'vue-router'
  import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
 <div class="grid grid-cols-1" id="main">
	<header>
		<h1>Web Comics <span>by Mo Laughs</span></h1>
	</header>
	<main>
		<img src="/Untitled_2024_03_25.png" />
		<div class="nav">
			<a href="#">Previous</a>
			<span>
				Untitled_2024_03_25.png
			</span>
			<a href="#">Next</a>
		</div>
	</main>
  </div>

</template>

<style scoped>
.grid#main {
	margin: 0 40px;

	header {
		h1 span {
			font-size: 0.6em;
			font-family: serif;
			font-style: italic;
		}
	}

	main {
		img {
			border: 1px solid black;
		}

		.nav {
			text-align: center;
			margin: 10px 0;

			* {
				padding: 0 15px;
			}
		}
	}

	a {
		color: blue;
		text-decoration: underline;
	}
}
</style>
