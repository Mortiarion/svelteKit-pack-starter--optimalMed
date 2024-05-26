<script lang="ts">
	import { cn } from '$lib/utils/cn';
	import type { ParagraphsType } from '$lib/types';

	export let classes = '';
	// export let paragraph: string;
</script>

<p class={cn('', classes)}>
	<!-- {paragraph} -->
	<slot />
</p>
