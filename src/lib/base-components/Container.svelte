<script lang="ts">
	import { cn } from '$lib/utils/cn';

    export let classes = '';
</script>

<div class={cn('mx-auto 2xl:max-w-screen-2xl', classes)}>
    <slot />
</div>
