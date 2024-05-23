<script lang="ts">
	import type { SectionWorkData } from '$lib/types';
	import Section from '$lib/base-components/Section.svelte';
	import Container from '$lib/base-components/Container.svelte';

	export let data: SectionWorkData;
</script>

<Section>
	<Container classes="2xl:max-w-3xl">
		<div class="article__flex-box">
			<div class="mb-5 flex flex-col gap-5">
				<h6 class="text-3xl font-bold">
					{data.heading}
					<span class=" text-biruza">{data.subtitle}</span>
				</h6>
				<p>{data.paragraph1}</p>
				<p>{data.paragraph2}</p>
			</div>
		</div>
	</Container>
</Section>
