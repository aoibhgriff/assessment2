<script>
	import actors from '$lib/data/actors.json';
</script>

<svelte:head>
	<title>Squid Game - Actors</title>
</svelte:head>

<div class="actors-page">
	<h1>ACTORS</h1>
	<div class="actors-grid">
		{#each actors as actor (actor.id)}
			<div class="actor-card">
				<div class="image-container">
					<img src={actor.image} alt={actor.actor} />
				</div>
				<div class="info-container">
					<h2 class="actor-name">{actor.actor}</h2>
					<p class="character-name">{actor.character}</p>
					<p class="player-number">Player {actor.playerNumber}</p>
					<p class="bio">{actor.description}</p>
				</div>
			</div>
		{/each}
	</div>
</div>

<style>
	.actors-page {
		padding: 2rem;
		max-width: 1400px;
		margin: 0 auto;
	}

	h1 {
		font-family: Megrim, sans-serif;
		font-size: 3rem;
		letter-spacing: 0.4rem;
		color: white;
		text-align: center;
		margin-bottom: 2rem;
		padding: 0;
	}

	.actors-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
		gap: 2rem;
		margin-bottom: 2rem;
	}

	.actor-card {
		background-color: rgba(0, 0, 0, 0.6);
		border-radius: 12px;
		overflow: hidden;
		transition: transform 0.3s ease, box-shadow 0.3s ease;
		display: flex;
		flex-direction: column;
		height: 100%;
	}

	.actor-card:hover {
		transform: translateY(-8px);
		box-shadow: 0 12px 24px rgba(227, 10, 90, 0.3);
	}

	.image-container {
		width: 100%;
		height: 300px;
		overflow: hidden;
		flex-shrink: 0;
	}

	.image-container img {
		width: 100%;
		height: 100%;
		object-fit: cover;
		display: block;
	}

	.info-container {
		padding: 1.5rem;
		display: flex;
		flex-direction: column;
		gap: 0.75rem;
		flex-grow: 1;
	}

	.actor-name {
		font-family: Megrim, sans-serif;
		font-size: 1.5rem;
		letter-spacing: 0.2rem;
		color: white;
		margin: 0;
		padding: 0;
	}

	.character-name {
		font-family: Lato, sans-serif;
		font-size: 1.1rem;
		color: white;
		margin: 0;
		padding: 0;
		font-weight: 600;
	}

	.player-number {
		font-family: Lato, sans-serif;
		font-size: 0.95rem;
		color: #e30a5a;
		font-weight: bold;
		margin: 0;
		padding: 0;
	}

	.bio {
		font-family: Lato, sans-serif;
		font-size: 0.95rem;
		color: #d0d0d0;
		line-height: 1.6;
		margin: 0;
		padding: 0;
		flex-grow: 1;
	}

	@media (max-width: 768px) {
		.actors-page {
			padding: 1rem;
		}

		h1 {
			font-size: 2rem;
			margin-bottom: 1.5rem;
		}

		.actors-grid {
			grid-template-columns: 1fr;
			gap: 1.5rem;
		}

		.actor-name {
			font-size: 1.3rem;
		}

		.character-name,
		.player-number,
		.bio {
			font-size: 0.9rem;
		}
	}

	@media (max-width: 480px) {
		h1 {
			font-size: 1.5rem;
			letter-spacing: 0.2rem;
		}

		.info-container {
			padding: 1rem;
			gap: 0.5rem;
		}

		.actor-name {
			font-size: 1.1rem;
		}

		.character-name,
		.player-number,
		.bio {
			font-size: 0.85rem;
		}

		.image-container {
			height: 250px;
		}
	}
</style>
