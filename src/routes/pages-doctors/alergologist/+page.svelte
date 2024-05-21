<!-- <h1>ALERGOLOGIST</h1> -->

<script lang="ts">
	import Bredcrambs from '../base/components/Bredcrumbs.svelte';
	import type { BreadcrumbData } from '$lib/types.ts';
    import SectionWork from '../base/components/SectionWork.svelte';

	let BreadcrumbData: BreadcrumbData = {
		bredCrumbsHead: 'Головна',
		bredCrumbsCategories: 'Работа аллергологом в Польщі'
	};
    
</script>

<Bredcrambs data={BreadcrumbData} />
<!-- <SectionWork  /> -->
