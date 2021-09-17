<template>
	<div class="image-container">
		<img src="../assets/Jumbotron.jpg" alt="" />
		<h2>{{ msg }}</h2>
	</div>
</template>

<script>
export default {
	name: 'Hero',
	props: {
		msg: String,
	},
};
</script>

<style scoped>
.image-container {
	width: 60%;
	margin: 0 auto;
	height: 300px;
}

.image-container img {
	width: 100%;
}
</style>
