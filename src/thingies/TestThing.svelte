<script>
    import Counter from "./Counter.svelte";
    let bigrat = "/bigrat.jpg"
    let bigrat_alt = "a big rat"
</script>

<main>
    not main thing

    <Counter />

    <img src={bigrat} alt={bigrat_alt}>
</main>

<style>
    main {
        text-align: center;
    }
</style>
