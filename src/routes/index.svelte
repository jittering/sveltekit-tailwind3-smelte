<script lang="ts">
	import { Button, Card, Chip, Image } from 'smelte';
</script>

<h1 class="p-4">Welcome to SvelteKit</h1>
<p class="my-custom-clazz border-2 m-4 p-4">
	Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>

<div class="p-20">
	<h2>Hello, Smelte!</h2>
	<p class="text-primary-600">Nice to meet you!</p>

	<Button>Button</Button>

	<br />
	<br />

	<Chip icon="face" removable selectable>test</Chip>

	<br />
	<br />

	<div>
		<Card.Card class="dark:bg-gray-200">
			<div slot="title">
				<Card.Title
					title="The three little kittens"
					subheader="A kitten poem"
					avatar="https://placekitten.com/64/64"
				/>
			</div>
			<div slot="media">
				<Image class="w-full" src="https://placekitten.com/300/200" alt="kitty" />
			</div>
			<div slot="text" class="p-5 pb-0 pt-3 text-gray-700 body-2">
				The three little kittens, they lost their mittens,<br />
				And they began to cry,<br />
				"Oh, mother dear, we sadly fear,<br />
				That we have lost our mittens."
			</div>
			<div slot="actions">
				<div class="p-2">
					<Button text>OK</Button>
					<Button text>Meow</Button>
				</div>
			</div>
		</Card.Card>
	</div>
</div>

<style lang="postcss">
	p.my-custom-clazz {
		color: green;
	}
</style>
