<script lang="ts">
    import Header from '../components/Header.svelte';
    import Footer from '../components/Footer.svelte';
</script>

<main>
    <Header />
    <slot />
    <Footer />
</main>

<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: "Roboto", sans-serif;
    }

    main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        /* background-color: #fffcf3; */
        max-width: 1280px;
        margin: 0 auto;
        padding: 1rem;
    }

    @media screen and (max-width: 600px) {
        main {
            padding: 0.5rem;
        }
    }
</style>