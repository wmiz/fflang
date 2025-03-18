<script>
  import "../app.css";
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
  import { fade } from "svelte/transition";

  import Construction from "../components/HomePage/Construction.svelte";

  import { onMount } from "svelte";
  let visible = false;
  onMount(() => {
    requestAnimationFrame(() => {
      setTimeout(() => {
        visible = true;
      }, 0);
    });
  });
</script>

<div class="font-heading">
  <img src="" alt="">
  <Construction />
  <!-- <Header />
  {#if visible}
    <div in:fade={{ duration: 125 }}>
      <slot />
    </div>
  {:else}
    <div class="h-screen bg-white">
    </div>
  {/if}
  <Footer /> -->
</div>
