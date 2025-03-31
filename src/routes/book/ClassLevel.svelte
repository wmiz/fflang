<script>
  export let level;
  export let sectionClass;
  import ClassOption from "./ClassOption.svelte";

  let color = "#edf7ef";
  let textColor = "rgb(27, 59, 92)";
  if (level.level == 1) {
    color = "rgb(238, 242, 247)";
  } else if (level.level == 2) {
    color = "#edf7ef";
    textColor = "rgb(42, 141, 78)";
  } else if (level.level == 3) {
    color = "#f5f0fb";
    textColor = "rgb(102, 51, 153)";
  }
</script>

<div
  class="md:py-12 {sectionClass} md:p-8 lvl-bg"
  style="background-color: {color}"
>
  <div class="container mx-auto px-4">
    <h2
      class="md:text-4xl text-3xl font-bold mb-4 underline text-left"
      style="color: {textColor}"
    >
      Level {level.level}: {level.title}
    </h2>
    <p class="mb-4 md:text-lg text-left">{level.description}</p>
    <p class="mb-4 md:text-lg text-left">
      <span class="font-bold">To Book:</span> Please email me at reed@fastandfunlanguage.com
    </p>
    <div class="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
      {#each level.classes as classOption}
        <ClassOption {classOption} date={classOption.startDate} btnColor={textColor} level={level} />
      {/each}
    </div>
    <p class="mt-12 text-xl font-bold">
      Please email me for multi-student discounts: <a
        class="underline text-[#1877F2]"
        href="mailto:reed@fastandfunlanguage.com">reed@fastandfunlanguage.com</a
      >
    </p>
  </div>
</div>
