<script lang="ts">
	import type { BreadcrumbData } from "$lib/types";
	export let data: BreadcrumbData;
</script>

<section>
	<div class="container mx-auto">
		<div class="breadcrumbs">
			<ul class="breadcrumbs__list flex px-6">
				<li><a href="/" class="text-bredcrambs text-sm">{data.bredCrumbsHead}</a></li>
				<li><span class="text-grey">{data.bredCrumbsCategories}</span></li>
			</ul>
		</div>
	</div>
</section>

<style lang="postcss">
	.text-bredcrambs::after {
		content: '>';
		width: 20px;
		height: 20px;
		margin: 0 10px;
		color: #080808;
	}
</style>
