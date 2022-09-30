<script>
    import { page } from '$app/stores';
</script>

<h1>Something's wrong</h1>

<h2>{$page.status}: {$page.error.message}</h2>