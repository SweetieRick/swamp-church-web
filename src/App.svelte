<script lang="ts">
  import { fade } from 'svelte/transition'
  // import { InviteButton } from './lib/InviteButton.svelte'
</script>

<main>
  <div class="title-container" id="title-container-box">
    <img 
      src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/11031417-71ef-493e-a9dc-4f9bb0b843eb/ddn12c3-172d16f0-c31c-48d9-bc84-a411522c32b2.png/v1/fill/w_1280,h_854,q_80,strp/shrek_s_swamp_by_naouriredouane1998_ddn12c3-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9ODU0IiwicGF0aCI6IlwvZlwvMTEwMzE0MTctNzFlZi00OTNlLWE5ZGMtNGY5YmIwYjg0M2ViXC9kZG4xMmMzLTE3MmQxNmYwLWMzMWMtNDhkOS1iYzg0LWE0MTE1MjJjMzJiMi5wbmciLCJ3aWR0aCI6Ijw9MTI4MCJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.nWesVNP50-_LKTKrTAt1P6KZw2oKxRV750iB3XII3Kk" 
      alt="Shrek's Church"
      class="header-img"
    >

    <h1 class="title-main" transition:fade="{{delay: 250}}">
      Swamp Church
    </h1>

    <h3 class="didascaly" transition:fade>
      The home of Shrek's followers
    </h3>

  </div>

</main>

<style>
  :root {
    background-color: rgb(44, 47, 51);
  }

  #title-container-box {
    position: relative;
  }

  .header-img {
    display: block;
    width: 100%;
    height: auto;
    opacity: 0.2;
    align-items: center;
    position: absolute;
  }

  .title-main {
    text-align: center;
    font-family:' Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 80px;

    margin: auto;
    width: 50%;
    padding: 450px;

    color: beige;
    position: absolute;
  }

  .didascaly {
    text-align: center;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 20px;

    margin: auto;
    width: 50%;
    padding: 450px;

    color: beige;
    position: absolute;
  }

</style>
