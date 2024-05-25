<!-- <h1>ANESTESIOLOGIST</h1> -->

<script lang="ts">
	import type {
		ListItemData,
		SectionPrimaryType,
		BreadcrumbData,
		SectionWorkData,
		SectionDutiesData
	} from '$lib/types';

	import Breadcrumb from '$lib/components/components-pages-doctors/Bredcrumbs.svelte';
	import SectionWork from '$lib/components/components-pages-doctors/SectionWork.svelte';
	import SectionDuties from '$lib/components/components-pages-doctors/SectionDuties.svelte';
	import SectionPrimary from '$lib/components/components-pages-doctors/SectionPrimary.svelte';
	import SectionImage from '$lib/components/components-pages-doctors/SectionImage.svelte';

	export let data: {
		BreadcrumbData: BreadcrumbData;
		SectionWorkData: SectionWorkData;
		SectionPrimaryData: SectionPrimaryType;
		SectionDutiesData: SectionDutiesData;
		SectionDutiesListData: ListItemData[];
		ListData: ListItemData[];
		ListData2: ListItemData[];
	};
</script>

<Breadcrumb data={data.BreadcrumbData} />
<SectionWork data={data.SectionWorkData} />
<SectionDuties data={{ SectionDutiesData: data.SectionDutiesData, SectionDutiesListData: data.SectionDutiesListData }} />
<SectionImage />
<SectionPrimary data={{ SectionPrimaryData: data.SectionPrimaryData, ListData: data.ListData, ListData2: data.ListData2 }} />
