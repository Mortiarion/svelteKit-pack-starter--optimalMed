<script lang="ts">
	import type { SectionDutiesData } from '$lib/types';
	import Section from '$lib/base-components/Section.svelte';
	import Container from '$lib/base-components/Container.svelte';
	import List from '$lib/base-components/List.svelte';

	export let data: SectionDutiesData;
</script>

<Section>
	<Container classes="2xl:max-w-3xl">
		<div class="flex flex-col gap-5">
			<h6 class="text-3xl font-bold">
				{data.heading}
				<span class="text-biruza">{data.subtitle}</span>
			</h6>
			<p>
				{data.paragraph}
			</p>

			<ul class=" mb-5 list-disc pl-5">
				<li>
					{data.list1}
				</li>
				<li>
					{data.list2}
				</li>
				<li>
					{data.list3}
				</li>
				<li>
					{data.list4}
				</li>
				<li>
					{data.list5}
				</li>
				<li>
					{data.list6}
				</li>
				<li>
					{data.list7}
				</li>
				<li>
					{data.list8}
				</li>
				<li>
					{data.list9}
				</li>
			</ul>
		</div>
	</Container>
</Section>
