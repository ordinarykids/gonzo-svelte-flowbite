<script>
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, ImagePlaceholder, Skeleton, TextPlaceholder } from 'flowbite-svelte'
</script>

<div class="relative px-8">
	<Navbar
		navClass="px-2 sm:px-4 py-2.5 absolute w-full z-20 top-0 left-0 border-b"
		let:hidden
		let:toggle
	>
		<NavBrand href="/">
			<span class="crazy-type self-center whitespace-nowrap text-4xl  dark:text-white">OTHER.SH</span>
		</NavBrand>
		<NavHamburger on:click={toggle} />
		<NavUl {hidden}>
			<NavLi class="" href="/" active={true}>ART</NavLi>
			<NavLi href="/shit" active={true}>CODE</NavLi>
			<!-- <NavLi href="/about">Real Shit</NavLi>
			<NavLi href="/services">Socia</NavLi>
			<NavLi href="/pricing">Pricing</NavLi>
			<NavLi href="/contact">Contact</NavLi> -->
		</NavUl>
	</Navbar>
	
</div>