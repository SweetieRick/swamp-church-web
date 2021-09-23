<script lang="ts">
  import { fade } from 'svelte/transition'
</script>

<main>
  <h1 transition:fade>
    Swamp Church
  </h1>
</main>

<style>
  :root {
    background-color: rgb(44, 47, 51);
  }

  h1 {
    text-align: center;
    font-family:' Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 60px;
    margin: 250px 250px 250px 250px;
  }
</style>
