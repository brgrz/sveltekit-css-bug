<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<sl-card class="card-overview">
	<img slot="image" src="https://placeimg.com/640/480/nature/grayscale" alt="alt" />

	<strong>Mittens</strong><br />
	This kitten is as cute as he is playful. Bring him home today!<br />
	<small>6 weeks old</small>

	<div slot="footer">
		<sl-button type="primary" pill>More Info</sl-button>
		<sl-rating />
	</div>
</sl-card>

<style>
	.card-overview {
		width: 300px;
	}

	.card-overview small {
		color: var(--sl-color-neutral-500);
	}

	.card-overview [slot='footer'] {
		display: flex;
		justify-content: space-between;
		align-items: center;
	}
</style>
