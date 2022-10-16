<script>
	import Card from "./Card.svelte";
	export let title;
	export let time;
	export let host;
</script>

<Card {title} location="Conference Room" {time} subtitle={' Hosted by: ' + host}></Card>
