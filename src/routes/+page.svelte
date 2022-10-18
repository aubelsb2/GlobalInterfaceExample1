<script lang="ts">
    import {ListItem} from "$components/ListItem.svelte";
    import ListItemComponent from "$components/ListItem.svelte";

    const list : Array<ListItem> = [
        { Name: "a", },
    ]
</script>

<ul>
    {#each list as i}
        <ListItemComponent li={i} />
    {/each}
</ul>
