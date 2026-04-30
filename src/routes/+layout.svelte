<script>
    import Nav from "$lib/components/Nav.svelte";
    import Footer from "$lib/components/Footer.svelte";

    let { children } = $props();
</script>

<Nav />

<main class="container">
    {@render children?.()}
</main>

<Footer />
``

<style>
    .container {
        max-width: 960px;
        margin: auto;
        padding: 1.5rem;
    }
</style>
