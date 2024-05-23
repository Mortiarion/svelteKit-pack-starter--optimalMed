<!-- <h1>ANESTESIOLOGIST</h1> -->

<script lang="ts">
	import Breadcrumb from '$lib/components/components-pages-doctors/Bredcrumbs.svelte';
	import SectionWork from '$lib/components/components-pages-doctors/SectionWork.svelte';
	import SectionDuties from '$lib/components/components-pages-doctors/SectionDuties.svelte';
	import SectionPrimary from '$lib/components/components-pages-doctors/SectionPrimary.svelte';
	import SectionImage from '$lib/components/components-pages-doctors/SectionImage.svelte';

	export let data;
</script>

<Breadcrumb data={data.BreadcrumbData} />
<SectionWork data={data.SectionWorkData} />
<SectionDuties {data} />
<SectionImage />
<SectionPrimary {data} />
