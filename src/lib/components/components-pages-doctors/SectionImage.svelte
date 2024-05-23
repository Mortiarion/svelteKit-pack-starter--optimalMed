<script lang="ts">
	import Section from '$lib/base-components/Section.svelte';
	import Container from '$lib/base-components/Container.svelte';
</script>

<Section classes="mb-5">
	<Container>
		<picture >
			<source
				srcset="/img/all-article-web-page-content-img/article-anestesiologist.avif"
				type="image/avif"
			/>
			<source
				srcset="/img/all-article-web-page-content-img/article-anestesiologist.webp"
				type="image/webp"
			/>
			<img class=" w-full"
				src="/img/all-article-web-page-content-img/article-anestesiologist.jpg"
				alt="article-anestesiologist"
			/>
		</picture>
	</Container>
</Section>
