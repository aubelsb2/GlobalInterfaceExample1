<script lang="ts" context="module">
    export interface ListItem {
        Name: string
    }
</script>
<script lang="ts">
    export let li : ListItem
</script>
<li>
    {li.Name}
</li>