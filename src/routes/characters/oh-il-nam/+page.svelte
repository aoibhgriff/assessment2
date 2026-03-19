<script>
</script>

<div class="character-page">
	<div class="layout-imageLeft">
		<div class="image-container">
			<img src="/images/Oh_Il-nam.jpg" alt="Oh Il-nam" />
		</div>
		<div class="text-container">
			<h1>Oh Il-nam</h1>
			<p class="player-number">Player 001</p>
			<p class="actor">Actor: Lee Byung-hun</p>
			<p class="bio">
				Oh Il-nam is an elderly man with a quiet demeanor who befriends Seong Gi-hun early in the
				games. Despite his age and frail appearance, he proves to be far more than he initially
				seems. Il-nam is thoughtful and compassionate, showing kindness to fellow players even as
				the competition becomes increasingly brutal. His calm wisdom and strategic thinking help
				him survive the games, while his genuine care for others reveals his deeper humanity. As
				the games progress, Il-nam becomes a pivotal figure whose true nature and motivations
				challenge everything the players believe about the competition.
			</p>
		</div>
	</div>
</div>

<style>
	.character-page {
		padding: 2rem;
		max-width: 1200px;
		margin: 0 auto;
	}

	.layout-imageLeft {
		display: flex;
		gap: 2rem;
		align-items: flex-start;
	}

	.image-container {
		flex: 0 0 40%;
		min-width: 300px;
	}

	.image-container img {
		width: 100%;
		height: auto;
		display: block;
		border-radius: 8px;
	}

	.text-container {
		flex: 1;
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}

	h1 {
		font-family: Megrim, sans-serif;
		font-size: 2.5cqw;
		letter-spacing: 0.4rem;
		color: white;
		margin: 0;
		padding: 0;
	}

	.player-number {
		font-family: Lato, sans-serif;
		font-size: 1.5cqw;
		color: #e30a5a;
		font-weight: bold;
		margin: 0;
		padding: 0;
	}

	.actor {
		font-family: Lato, sans-serif;
		font-size: 1.2cqw;
		color: white;
		margin: 0;
		padding: 0;
	}

	.bio {
		font-family: Lato, sans-serif;
		font-size: 1.2cqw;
		color: white;
		line-height: 1.7em;
		margin: 0;
		padding: 0;
	}

	@media (max-width: 768px) {
		.layout-imageLeft {
			flex-direction: column;
		}

		.image-container {
			flex: 1;
			min-width: auto;
		}

		h1 {
			font-size: 2rem;
		}

		.player-number,
		.actor,
		.bio {
			font-size: 1rem;
		}
	}
</style>
