<script lang="ts">
    export let call;
    let dcall = call ?? 'Hello';

    export let name;
    let dname = name ?? 'hello';

    export let prompt;
    let dprompt = prompt ?? 'can you hear me?';

</script>

<h2>{dcall} {dname}, {dprompt}</h2>