<script context="module" lang="ts">
    import Info from '../components/Info.svelte'
    export const prerender = true;
</script>
<section>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Info />
<Info name="Yuki" />
<Info name="K" prompt="stay well out there, buddy."/>
<Info call="Yo" name="Amia" prompt="you good?"/>

</section>