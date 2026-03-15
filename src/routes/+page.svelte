<script lang="ts">
	import { resolve } from '$app/paths';
	import { cn } from '@utils/cn';
</script>

<div class={cn('flex h-screen w-full flex-col items-center justify-center', 'aspect-auto')}>
	<h1 class="text-4xl font-bold text-red-500">Welcome to SvelteKit</h1>

	<a href={resolve('/about')} class="text-blue-500">About</a>
</div>
