<script>

    let { value = $bindable("") } = $props();

    function autoResize(e) {
        e.target.style.height = "auto";   // reset
        e.target.style.height = e.target.scrollHeight + "px"; // grow to fit
    }
</script>

<textarea class="beveledmd" bind:value oninput={autoResize} placeholder="Blog here...">

</textarea>

<style>
    textarea {
        padding: 20px;
        resize: none;
        overflow: hidden;
        font-family: monospace;
        font-size: 1rem;
    }
</style>