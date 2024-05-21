<script lang="ts">
	import type { SectionDutiesData } from '$lib/types';

	export let data: SectionDutiesData;
</script>

<section>
	<div class="container max-w-3xl m-auto">
		<div class="flex flex-col gap-5">
			<h6 class="font-bold text-3xl">
				{data.heading}
				<span class="text-biruza">{data.subtitle}</span>
			</h6>
			<p>
				{data.paragraph}
			</p>
			<ul class=" list-disc pl-5 mb-5">
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
	</div>
</section>
