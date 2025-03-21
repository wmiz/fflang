<script>
  import { slide } from 'svelte/transition';

  export let paragraphs = [];
  export let header = ''; // New prop for the header text
  let expanded = false;
</script>

<div class="w-1/3 text-xl p-8 shadow-lg border-4 bg-white rounded-xl">
  {#if paragraphs.length > 0}
    <p class="mb-2">{@html paragraphs[0]}</p>
    {#if expanded}
      <div transition:slide>
        {#each paragraphs.slice(1) as paragraph}
          <p class="mb-2">{@html paragraph}</p>
        {/each}
      </div>
    {/if}
    {#if paragraphs.length > 1} <!-- Only show button if there are multiple paragraphs -->
      <button
        on:click={() => expanded = !expanded}
        class="mt-2 text-xl uppercase cursor-pointer btn p-6 bg-[#000000] btn-primary w-full rounded-xl"
        aria-expanded={expanded}
      >
        {expanded ? 'Read Less...' : 'Read More...'}
      </button>
    {/if}
  {/if}
</div>