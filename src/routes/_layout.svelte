<script>
  import Nav from "../components/Nav.svelte";

  export let segment;
</script>

<Nav {segment} />

<main class="bg-adb-background mx-auto my-0">
  <slot />
</main>
