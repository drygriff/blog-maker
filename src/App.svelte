<script>
    import KeywordList from "./KeywordList.svelte";
    import TextEntry from "./TextEntry.svelte";

</script>

<div>
    <KeywordList/>
    <TextEntry/>
</div>

<style>
    div {
        display: flex;
        padding: 40px;
        gap: 40px;
    }

    div > :global(*) {
        min-width: 400px;
    }
</style>
