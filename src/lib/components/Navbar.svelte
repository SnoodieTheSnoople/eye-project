<script>
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>

<Navbar class='bg-primary-800 text-white'>
    <NavBrand href="/">
        <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Smart Readers</span>
    </NavBrand>
    <NavHamburger/>
    <NavUl >
        <NavLi href="/">Home</NavLi>
    </NavUl>
</Navbar>