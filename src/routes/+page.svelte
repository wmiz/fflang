<script>
  import Hero from "../components/HomePage/Hero.svelte";
  import Video from "../components/HomePage/Video.svelte";
  import ProblemSolution from "../components/HomePage/ProblemSolution.svelte";
  // import Door1 from "../components/HomePage/Door-1.svelte";
  // import Door2 from "../components/HomePage/Door-2.svelte";
  // import Door3 from "../components/HomePage/Door-3.svelte";
  import Classes from "../components/HomePage/3-classes.svelte";
  import Classes2 from "../components/HomePage/3-classes-2.svelte";
  import Stairs from "../components/HomePage/Stairs.svelte";
  import ClassStructure from "../components/HomePage/ClassStructure.svelte";
  import TeacherBio from "../components/HomePage/TeacherBio.svelte";
  import Tests from "../components/HomePage/Tests.svelte";
  import Testimonials from "../components/HomePage/Testimonials.svelte";
  import ThreeSteps from "../components/HomePage/ThreeSteps.svelte";
  import WhatYouGet from "../components/HomePage/WhatYouGet.svelte";
  import CTA from "../components/HomePage/CTA.svelte";
  import InnerTransformation from "../components/HomePage/InnerTransformation.svelte";
  import Screen from "../components/HomePage/Screen.svelte";
  import TestSlider from "../components/HomePage/TestSlider.svelte";
</script>

<div
  class="text-[#050505] m-0 md:mx-10 md:mb-10 md:mt-10 border-solid border-[#EE6352] md:border-[20px] border-[8px] md:rounded-xl shadow-xl"
>
  <div
    class="border-solid border-[#FAC05E] md:border-[20px] border-[6px]"
  >
    <div>
      <Hero />
    </div>
    <Video />
    <!-- <Tests /> -->
     <TestSlider />
    <Classes />

    <Testimonials />
      <InnerTransformation />

    <TeacherBio />

    <CTA />
  </div>
</div>
