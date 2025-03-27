<script>
    export let level;
    export let sectionClass;
    import ClassOption from './ClassOption.svelte';
  </script>
  
  <div class="md:py-12 {sectionClass} text-center md:border-2 md:border-gray-300 mb-10 md:p-8 rounded-xl ">
    <div class="container mx-auto px-4">
      <h2 class="md:text-5xl text-4xl font-bold mb-4 underline ">Level {level.level}: {level.title}</h2>
      <p class="mb-4 md:text-xl text-lg">{level.description}</p>
      <div class="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
        {#each level.classes as classOption}
          <ClassOption {classOption} />
        {/each}
      </div>
      <p class="mt-12 text-xl font-bold">Please email me for multi-student discounts: <a class="underline text-[#1877F2]" href="mailto:reed@fastandfunlanguage.com">reed@fastandfunlanguage.com</a></p>

    </div>
  </div>