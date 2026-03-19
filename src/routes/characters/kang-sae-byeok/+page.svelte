<script>
</script>

<div class="character-page">
	<div class="layout-imageTop">
		<div class="image-container">
			<img src="/images/HoYeonJung.jpg" alt="Kang Sae-byeok" />
		</div>
		<div class="text-container">
			<h1>Kang Sae-byeok</h1>
			<p class="player-number">Player 067</p>
			<p class="actor">Actor: Jung Ho-yeon</p>
			<p class="bio">
				Kang Sae-byeok is a young North Korean defector determined to win the games and secure a
				better life for herself and her family. Intelligent, resourceful, and fiercely
				independent, she navigates the deadly competition with remarkable composure and strategic
				thinking. Despite her youth, Sae-byeok demonstrates maturity beyond her years, having
				survived harrowing circumstances before entering the games. She forms meaningful
				connections with fellow players while maintaining her focus on survival. Sae-byeok's
				resilience, courage, and unwavering determination make her one of the most compelling
				players in the competition.
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

	.layout-imageTop {
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
