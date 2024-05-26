<script lang="ts">
	import { cn } from '$lib/utils/cn';
	import type { ListItemData } from '$lib/types';
	export let items: ListItemData[] = [];
	export let classes = '';
</script>

<ul class={cn('mb-5 flex list-disc flex-col gap-2 pl-5', classes)}>
	{#each items as item}
		<li class={cn('', classes)}>
			{item.text}
		</li>
	{/each}
</ul>
