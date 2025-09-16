<script>
    import KeywordEntry from "./KeywordEntry.svelte";

</script>


<div class="beveledmd">
    <h2>Keywords</h2>

    <ul>
        <KeywordEntry/>
    </ul>

</div>


<style>
    div {
        background-color: var(--secondary-color);
        padding: 0px 40px;
    }

    ul {
        margin: 0;
        padding: 0;
    }

    li {
        list-style: none;
        margin: 0;
        padding: 0;
    }
</style>