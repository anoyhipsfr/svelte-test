<script>
    let counter = 0

    function count() {
        counter += 1
    }
</script>

<main>
    <div>
        <button on:click={count}>count ({counter})</button>
    </div>
</main>
