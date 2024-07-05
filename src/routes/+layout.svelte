<script>
    import "../app.css"
</script>

<main>
    <slot />
</main>

<style lang="postcss">
    :global(html) {
        @apply bg-gray-200;
    }
</style>
