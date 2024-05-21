<!-- <h1>ALERGOLOGIST</h1> -->

<script lang="ts">
	import Bredcrambs from '$lib/components/components-pages-doctors/Bredcrumbs.svelte';
	import type { BreadcrumbData } from '$lib/types.ts';
    import SectionWork from '$lib/components/components-pages-doctors/SectionWork.svelte';

	let BreadcrumbData: BreadcrumbData = {
		bredCrumbsHead: 'Головна',
		bredCrumbsCategories: 'Работа аллергологом в Польщі'
	};
    
</script>

<Bredcrambs data={BreadcrumbData} />
<!-- <SectionWork  /> -->
