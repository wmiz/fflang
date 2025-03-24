<script>
  import { slide } from 'svelte/transition';

  export let paragraphs = [];
  export let header = ''; // New prop for the header text
  let expanded = false;
</script>

<div class="w-1/3 text-xl/tight p-8 shadow-2xl bg-white rounded-xl">
  {#if paragraphs.length > 0}
    <p class="mb-4">{@html paragraphs[0]}</p>
    {#if expanded}
      <div transition:slide>
        {#each paragraphs.slice(1) as paragraph}
          <p class="mb-4">{@html paragraph}</p>
        {/each}
      </div>
    {/if}
    {#if paragraphs.length > 1} <!-- Only show button if there are multiple paragraphs -->
      <button
        on:click={() => expanded = !expanded}
        class="mt-2 rounded-full text-2xl p-6 uppercase cursor-pointer btn bg-[#000000] btn-primary w-full"
        aria-expanded={expanded}
      >
        {expanded ? 'Read Less...' : 'Read More...'}
      </button>
    {/if}
  {/if}
</div>