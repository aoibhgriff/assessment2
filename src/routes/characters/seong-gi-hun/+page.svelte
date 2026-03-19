<script>
</script>

<div class="character-page">
	<div class="layout-textTop">
		<div class="text-container">
			<h1>Seong Gi-hun</h1>
			<p class="player-number">Player 456</p>
			<p class="actor">Actor: Lee Jung-jae</p>
			<p class="bio">
				Seong Gi-hun is an unemployed man deeply in debt who enters the games hoping to win enough
				money to turn his life around. Compassionate and empathetic despite his struggles, Gi-hun
				is driven by a desire to provide for his elderly mother and maintain a relationship with
				his daughter. He forms deep emotional connections with the people he meets in the games,
				often prioritizing others' welfare over his own survival. Gi-hun's moral compass and
				emotional intelligence guide his decisions throughout the competition. As the story
				unfolds, Gi-hun emerges as the emotional core of the narrative, embodying the human cost
				of desperation and the power of human connection even in the darkest circumstances.
			</p>
		</div>
		<div class="image-container">
			<img src="/images/SeongGi-hun.jpg" alt="Seong Gi-hun" />
		</div>
	</div>
</div>

<style>
	.character-page {
		padding: 2rem;
		max-width: 1200px;
		margin: 0 auto;
	}

	.layout-textTop {
		display: flex;
		flex-direction: column;
		gap: 2rem;
		align-items: center;
		margin: 0 auto;
	}

	.image-container {
		max-width: 500px;
		display: flex;
		justify-content: center;
	}

	.image-container img {
		width: 100%;
		height: auto;
		display: block;
		border-radius: 8px;
	}

	.text-container {
		display: flex;
		flex-direction: column;
		gap: 1rem;
		text-align: center;
		max-width: 600px;
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
