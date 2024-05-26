<!-- <h1>ALERGOLOGIST</h1> -->

<script lang="ts">
	import type {
		BreadcrumbType,
		SectionTitleTwoParagraphType,
		SectionTitleParListTwoParType,
		SectionTitleParListParType,
		SectionTitleParListParTypeTwo,
		SectionImageType
	} from '$lib/types';

	import Breadcrumb from '$lib/components/components-pages-doctors/Bredcrumbs.svelte';
	import SectionTitleTwoParagraph from '$lib/components/components-pages-doctors/SectionTitleTwoParagraph.svelte';
	import SectionTitleParListTwoPar from '$lib/components/components-pages-doctors/SectionTitleParListTwoPar.svelte';
	import SectionTitleParListPar from '$lib/components/components-pages-doctors/SectionTitleParListPar.svelte';
	import SectionImage from '$lib/components/components-pages-doctors/SectionImage.svelte';

	export let data: {
		BreadcrumbData: BreadcrumbType;
		SectionTitleTwoParagraphData: SectionTitleTwoParagraphType;
		SectionTitleParListTwoParData: SectionTitleParListTwoParType;
		SectionTitleParListParData: SectionTitleParListParType;
		SectionTitleParListParTypeTwoData: SectionTitleParListParTypeTwo;
		SectionImageData: SectionImageType;
	};
</script>

<Breadcrumb data={data.BreadcrumbData} />
<SectionTitleTwoParagraph data={data.SectionTitleTwoParagraphData} />
<SectionImage data={data.SectionImageData} />
<SectionTitleParListTwoPar data={data.SectionTitleParListTwoParData} />
<SectionTitleParListPar data={data.SectionTitleParListParData} />
<SectionTitleParListPar data={data.SectionTitleParListParTypeTwoData} />
