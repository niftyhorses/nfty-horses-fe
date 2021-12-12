<script>
    import PageTransition from "../components/PageTransition.svelte";
    import Nav from "../components/Nav.svelte";
    import Footer from "../components/Footer.svelte";

    export let key;
</script>

<script context="module">
    export const load = async ({ page }) => ({
      props: {
        key: page.path,
      },
    })
</script>

<div id="nh-wrapper">
    <Nav />
    <PageTransition refresh={key}>
        <slot />
    </PageTransition>
    <Footer />
</div>


<style>
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

    #nh-wrapper {
        display: grid;
        grid-template-rows: auto 1fr auto;
        min-height: 100vh;
    }
</style>