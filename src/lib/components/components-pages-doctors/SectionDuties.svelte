<script lang="ts">
	import type { SectionDutiesData, ListItemData } from '$lib/types';
	import Section from '$lib/base-components/Section.svelte';
	import Container from '$lib/base-components/Container.svelte';
	import List from '$lib/base-components/List.svelte';
	import Heading from '$lib/base-components/Heading.svelte';

	export let data: {
		SectionDutiesData: SectionDutiesData;
		SectionDutiesListData: ListItemData[];
	};
</script>

<Section>
	<Container classes="2xl:max-w-3xl">
		<div class="flex flex-col gap-5">
			<Heading level="h2" classes="text-3xl font-bold">
				{data.SectionDutiesData.heading}
				<span class="text-biruza">{data.SectionDutiesData.subtitle}</span>
			</Heading>
			<p>
				{data.SectionDutiesData.paragraph}
			</p>
			<List items={data.SectionDutiesListData} />
		</div>
	</Container>
</Section>
