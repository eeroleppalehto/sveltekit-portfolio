<script lang="ts">
    import SvelteLogo from 'virtual:icons/teenyicons/svelte-solid';
</script>

<footer>
    <p>©2023 Eero Leppälehto</p>
    <div class="footer-section">
        <p>Powered by SvelteKit</p>
        <SvelteLogo style="font-size:1rem" />
    </div>
    <a href="/">GitHub</a>
    <a href="/">LinkedIn</a>

</footer>

<style>
    footer {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        margin-top: 4rem;
    }

    .footer-section {
        display: flex;
        flex-direction: row;
        align-items: center;
        gap: 0.2rem;
    }
</style>