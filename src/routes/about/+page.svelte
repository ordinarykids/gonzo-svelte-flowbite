<script>
	import { AccordionItem, Accordion } from 'flowbite-svelte'
</script>



<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div >
	<Accordion>
		<AccordionItem>
			<span slot="header">My Header 1</span>
			<p class="mb-2 text-gray-500 dark:text-gray-400">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo ab necessitatibus sint explicabo ...</p>
			<p class="text-gray-500 dark:text-gray-400">Check out this guide to learn how to <a href="/" target="_blank" rel="noreferrer" class="text-blue-600 dark:text-blue-500 hover:underline">get started</a> and start developing websites even faster with components on top of Tailwind CSS.</p>
		</AccordionItem>
		<AccordionItem>
			<span slot="header">My Header 2</span>
			<p class="mb-2 text-gray-500 dark:text-gray-400">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo ab necessitatibus sint explicabo ...</p>
			<p class="mb-2 text-gray-500 dark:text-gray-400">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo ab necessitatibus sint explicabo ...</p>
			<p class="mb-2 text-gray-500 dark:text-gray-400">Learn more about these technologies:</p>
			<ul class="list-disc pl-5 dark:text-gray-400 text-gray-500">
				<li><a href="/" target="_blank" rel="noreferrer" class="text-blue-600 dark:text-blue-500 hover:underline" >Lorem ipsum</a></li>
				<li><a href="https://tailwindui.com/" rel="noreferrer" target="_blank"  class="text-blue-600 dark:text-blue-500 hover:underline">Tailwind UI</a></li>
			</ul>
		</AccordionItem>
	</Accordion>


	<h1>About this app</h1>

	<p>
		This is a <a href="https://kit.svelte.dev">SvelteKit</a> app. You can make your own by typing the
		following into your command line and following the prompts:
	</p>

	<pre>npm create svelte@latest</pre>

	<p>
		The page you're looking at is purely static HTML, with no client-side interactivity needed.
		Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
		the devtools network panel and reloading.
	</p>


</div>
