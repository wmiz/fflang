<script>
  import "../app.css";
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
  import { fade } from "svelte/transition";

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

<div class="font-heading bg-gradient-to-tr from-gray-50 to-gray-100">
  <Header />
  {#if visible}
    <div in:fade={{ duration: 125 }} class="max-w-[1400px] mx-auto">
      <slot />
    </div>
  {:else}
    <div class="h-screen bg-white">
    </div>
  {/if}
  <Footer />
</div>
