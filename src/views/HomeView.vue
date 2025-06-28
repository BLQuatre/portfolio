<script setup lang="ts">
import MetaballsBackground from '@/components/MetaballsBackground.vue';
import GithubIcon from '@/components/icons/GithubIcon.vue';
import LinkedInIcon from '@/components/icons/LinkedInIcon.vue';
</script>

<template>
	<main>
		<MetaballsBackground />
		<div class="container">
			<div class="title">Clems</div>
			<div class="subtitle">Student at 42 Le Havre</div>
			<div class="links">
				<a class="link" href="https://github.com/BLQuatre" target="_blank" rel="noopener noreferrer"><GithubIcon class="link-icon" /></a>
				<a class="link" href="www.linkedin.com/in/clement-auvray" target="_blank" rel="noopener noreferrer"><LinkedInIcon class="link-icon" /></a>
			</div>
		</div>
	</main>
</template>

<style scoped>
.container {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	width: 35vw;
	height: 35vh;
	overflow: hidden;
	border-radius: 25px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}
.container::before {
	content: "";
	position: absolute;
	inset: 0;
	background-color: rgba(0, 0, 0, 0.75);
	backdrop-filter: blur(10px);
	border-radius: 25px;
	z-index: -1;
}
.title {
	margin-top: 3vw;
	position: relative;
	font-size: 2.5em;
	font-weight: bold;
	color: #fff;
	text-align: center;
	margin-bottom: 0;
}
.subtitle {
	margin-top: 1vw;
	position: relative;
	font-size: 2em;
	font-weight: bold;
	color: #fff;
	text-align: center;
}
.links {
	margin-top: auto;
	margin-bottom: 3vw;
	position: relative;
	display: flex;
	align-items: center;
	justify-content: center;
	gap: 1em;
}
.link-icon {
	width: 4vw;
	height: 4vw;
	color: white;
	transition: color 0.2s ease-in-out;
}
.link-icon:hover {
	color: #3b82f6;
}
</style>
