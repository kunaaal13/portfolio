<script lang="ts">
	import { cn } from '@utils/cn';
	import { resolve } from '$app/paths';
</script>

<div class={cn('flex h-screen w-full flex-col items-start justify-center', 'aspect-auto')}>
	<h1 class="text-4xl font-bold text-red-500">About</h1>

	<a href={resolve('/')} class="text-blue-500">Home</a>
</div>
