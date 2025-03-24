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
  // import Testimonials from "../components/HomePage/Testimonials.svelte";
  import ThreeSteps from "../components/HomePage/ThreeSteps.svelte";
  import WhatYouGet from "../components/HomePage/WhatYouGet.svelte";
  import CTA from "../components/HomePage/CTA.svelte";
  import InnerTransformation from "../components/HomePage/InnerTransformation.svelte";
  import Screen from "../components/HomePage/Screen.svelte";
</script>

<div class="">
  <div
    class="text-[#000000] mx-10"
    style="border-right: solid; border-color:#e4492d;border-right-width: 20px;border-left: solid; border-color:#e4492d;border-left-width: 20px; border-top: solid; border-color:#e4492d;border-top-width: 20px;border-bottom: solid; border-color:#e4492d;border-bottom-width: 20px;"
  >
    <div
      style="border-right: solid; border-color:#efb100;border-right-width: 20px;border-left: solid; border-color:#efb100;border-left-width: 20px; border-top: solid; border-color:#efb100;border-top-width: 20px;border-bottom: solid; border-color:#efb100;border-bottom-width: 20px;"
    >
      <div>
        <Hero />
      </div>
      <Video />
      <Classes />
      <div class="border-b-4">
        <InnerTransformation />
      </div>

      <TeacherBio />

      <CTA />
    </div>
  </div>
</div>
