<script>
	export let title;
	export let location;
	export let time;
	export let subtitle = "";
</script>


<div class="total-flex">
	<h3>
		{time}
	</h3>
<div class="card">
	<h3>
		{title}
	</h3>
	<p>
		= {location}
	</p>
	{#if subtitle}
	<p>
		{subtitle}
	</p>
	{/if}
</div>
</div>


<style>
	.card {
		background: white;
		border-radius: 10px;
		padding: 0.5rem 1rem;
		color: black;
		width: 25rem;
	}
	
	h3,p {
		margin: 0.25rem;
	}
	
	p {
		margin-top: 0.5rem;
	}
	
	.total-flex {
		display: flex;
		width: 100%;
		align-items: center;
		gap: 1rem;
	}
</style>