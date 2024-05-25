<script lang="ts">
	import type { ListItemData, SectionPrimaryType } from '$lib/types';
	import Section from '$lib/base-components/Section.svelte';
	import Container from '$lib/base-components/Container.svelte';
	import List from '$lib/base-components/List.svelte';
	import Heading from '$lib/base-components/Heading.svelte';

	export let data: {
		ListData: ListItemData[];
		ListData2: ListItemData[];
		SectionPrimaryData: SectionPrimaryType;
	};
</script>

<Section>
	<Container classes="2xl:max-w-3xl">
		<div class="primary-requirements">
			<p class="mb-5">
				{data.SectionPrimaryData.paragraph}
			</p>
			<p class="mb-5">
				{data.SectionPrimaryData.paragraph2}
			</p>
			<Heading level="h2" classes="mb-5 text-3xl font-bold">
				{data.SectionPrimaryData.title}
				<span class=" text-biruza">{data.SectionPrimaryData.subtitle}</span>
			</Heading>
			<p class="mb-5">
				{data.SectionPrimaryData.paragraph3}
			</p>
			<List items={data.ListData} />
			<p class="mb-5">
				{data.SectionPrimaryData.paragraph4}
			</p>
			<Heading level="h2" classes="mb-5 text-3xl font-bold">
				{data.SectionPrimaryData.title1}
				<span class="text-biruza">{data.SectionPrimaryData.subtitle1}</span>
			</Heading>
			<p class="mb-5">
				{data.SectionPrimaryData.paragraph5}
			</p>
			<List items={data.ListData2} />
			<p class="mb-5">
				{data.SectionPrimaryData.paragraph6}
			</p>
		</div>
	</Container>
</Section>
