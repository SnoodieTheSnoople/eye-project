<script>
	import Modal from "$lib/components/Modal.svelte";
import { Button } from "flowbite-svelte";
</script>
<!-- 
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p> -->

<div class='my-10 mx-4 space-y-8'>
	<h1 class='flex justify-center items-center font-bold text-4xl'>Welcome to Smart Readers!</h1>

	<div class='flex justify-center items-center'>
		<!-- <Button>Get Started</Button> -->
		<Modal/>
	</div>
	
	<div class='space-y-4'>
		<h2 class='flex justify-center items-center font-bold text-2xl'>About</h2>
		<p class='text-center'>Smart Readers is a tool that allows you to understand your reading glasses prescription.</p>
	</div>
</div>