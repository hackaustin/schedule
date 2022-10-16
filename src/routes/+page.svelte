<script>
	import Card from "../components/Card.svelte";
	import Workshop from "../components/Workshop.svelte"
	import BlankCard from "../components/BlankCard.svelte"
</script>

<h1 class="ha-heading">
Hack Austin!	
</h1>
<h2>
	Schedule
</h2>
<div>
	<Card title="✅ Check-in & Lobby" location="Front Porch" time="10:00"></Card>
	<Card title="👋 Opening Ceremony" location="Projector Screen" time="10:30"></Card>
	<Card title="👥 Team formation" location="Open Area" time="11:00"></Card>
	<BlankCard time="11:20"></BlankCard>
	<Card title="🍕 Lunch & ❓ Trivia" location="Bar" subtitle="📌 Trivia: Projector Screen, starts at 12:30" time="12:00"></Card>
	<Workshop title="🌐 Personal Website Workshop - highly recommended" time="13:30" host="Reese Armstrong"></Workshop>
	<Workshop title="🐍 Intro to Python Workshop" time="14:15" host="Suhas Voolla"></Workshop>
	<Workshop title="🎮 Sprig Workshop - make a game!" host="Reese Armstrong" time="14:45"></Workshop>
	<Workshop title="⬜ 3D Modeling Workshop" host="Camilla Bosquez" time="15:30"></Workshop>
	<Workshop title="🎮 Unity Workshop" host="Arnav Jambhulkar" time="16:30"></Workshop>
	<Workshop title="Swift Workshop" host="Rylan Berry" time="17:00"></Workshop>
	<BlankCard time="17:30"></BlankCard>
	<Card title="🙌 Hands off! - Demo Setup & More Pizza 🍕" location="Everywhere" time="18:00"></Card>
	<Card title="💻 Demos & Voting" location="Open Area" time="18:30"></Card>
	<Card title="🏁 Closing Ceremony" location="Projector Screen" time="19:15"></Card>
	<Card title="🏃 Good bye!" location="Front exit" time="19:30"></Card>
	
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300..700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap');

	:root {
			--primary-green: #37F17A;
			--darker-green: #20964B;
			--darkest-green: #154125;
	}

	* {
			font-family: 'Space Grotesk', sans-serif;
			letter-spacing: -0.035em;
			color: white;
	}
	:global(body) {
		background-color: black;
	}
	.ha-heading {
		text-transform: uppercase;
		color: var(--primary-green);
		text-align: center;
	}
	
	div {
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}
</style>
