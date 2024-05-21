<script lang="ts">
	import type { SectionWorkData } from '$lib/types';

	export let data: SectionWorkData;
</script>

<section>
	<div class="container m-auto max-w-3xl">
		<div class="article__flex-box">
			<div class="flex flex-col gap-5 mb-5">
				<h6 class="font-bold text-3xl">
					{data.heading}
					<span class=" text-biruza">{data.subtitle}</span>
				</h6>
				<p>{data.paragraph1}</p>
				<p>{data.paragraph2}</p>
			</div>
		</div>
	</div>
</section>
