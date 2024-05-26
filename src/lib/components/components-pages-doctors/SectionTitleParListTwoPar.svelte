<script lang="ts">
    import Section from '$lib/base-components/Section.svelte';
	import Container from '$lib/base-components/Container.svelte';
	import Heading from '$lib/base-components/Heading.svelte';
	import Text from '$lib/base-components/Text.svelte';
	import Paragraph from '$lib/base-components/Paragraph.svelte';
    import List from '$lib/base-components/List.svelte';
	import type { SectionTitleParListTwoParType } from '$lib/types';
	export let data: SectionTitleParListTwoParType;
</script>

<Section>
	<Container classes="mx-auto 2xl:max-w-3xl">
		<div class="mb-5 flex flex-col gap-5">
			<Heading level="h3" classes="text-3xl font-bold">
				{data.title}
				<!-- Посадові  -->
				<Text classes="text-biruza">{data.subtitle}
					<!-- обов'язки анестезіолога -->
				</Text>
			</Heading>
			<Paragraph>
				{data.paragraph__one}
				<!-- Повна назва цієї спеціалізації звучить як "анестезіолог-реаніматолог". Лікар цього профілю працює з усіма видами анестезії, а також займається веденням інтенсивної терапії. Таким чином, іноземні громадяни, які отримали роботу анестезіологами в Польщі: -->
			</Paragraph>
            <List items={data.list} />
			<Paragraph>
				{data.paragraph__two}
				<!-- Кваліфікований анестезіолог має вміти працювати з усіма видами анестезії - загальною (так званим наркозом), регіонарною та місцевою. -->
			</Paragraph>
			<Paragraph>
				<!-- Вільні вакансії лікаря-анестезіолога в Польщі є у відділеннях інтенсивної терапії в державних і приватних закладах стаціонарного типу, а також в амбулаторіях, обладнаних власними малими операційними. -->
				{data.paragraph__three}
			</Paragraph>
		</div>
	</Container>
</Section>