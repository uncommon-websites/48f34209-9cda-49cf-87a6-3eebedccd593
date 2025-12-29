<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen bg-white text-black font-sans px-6 py-8 md:px-10 md:py-10 flex items-center justify-center">
	<div class="max-w-2xl text-center">
		<h1 class="text-6xl md:text-8xl font-normal mb-4 text-gray-900">Error {page.status}</h1>
		<p class="text-lg md:text-xl text-gray-600 mb-8">{page.error?.message ?? "Something went wrong."}</p>
		<a href="/" class="inline-block text-primary-600 hover:text-primary-700 transition-colors text-[15px]">← Go back home</a>
	</div>
</main>
