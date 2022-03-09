<script lang="ts">
	import NavBar from "./NavBar.svelte";
	import ListArticle from "./listArticle.svelte";
	import Article from "./article.svelte";

	let article = [
		{ name: 'Chaise', description: 'Chaise faite de cuir, couture fait main et pied en acajou.', price: '54', img: './img/chaise.jpeg' },
		{ name: 'Voiture', description: '4x4 famillial tout équipé.', price: '72 000', img: './img/voiture.jpg' },
		{ name: 'sac', description: 'Sac en tissu avec renfort et laniére en cuir.', price: '32', img: './img/sac.jpg' },
		{ name: 'Télé', description: '8k OLED pliable.', price: '1000', img: './img/télé.jpg' }
	];
</script>

<NavBar />
<ListArticle>
	<Article />
</ListArticle>

<style>
</style>