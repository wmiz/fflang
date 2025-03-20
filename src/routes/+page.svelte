<script>
  import Hero from "../components/HomePage/Hero.svelte";
  import Video from "../components/HomePage/Video.svelte";
  import ProblemSolution from "../components/HomePage/ProblemSolution.svelte";
  import Door1 from "../components/HomePage/Door-1.svelte";
  import Door2 from "../components/HomePage/Door-2.svelte";
  import Door3 from "../components/HomePage/Door-3.svelte";
  import Classes from "../components/HomePage/3-classes.svelte";
  import Classes2 from "../components/HomePage/3-classes-2.svelte";
  import Stairs from "../components/HomePage/Stairs.svelte";
  import ClassStructure from "../components/HomePage/ClassStructure.svelte";
  import TeacherBio from "../components/HomePage/TeacherBio.svelte";
  import Testimonials from "../components/HomePage/Testimonials.svelte";
  import ThreeSteps from "../components/HomePage/ThreeSteps.svelte";
  import WhatYouGet from "../components/HomePage/WhatYouGet.svelte";
  import CTA from "../components/HomePage/CTA.svelte";
  import InnerTransformation from "../components/HomePage/InnerTransformation.svelte";
</script>

<div class="text-[#16455c] bg-gray-100">
  <Hero />
  <Video />
  <Door1 />
  <Door2 />
  <Door3 />
  <Classes />
  <div class="border-b-4">
    <Classes2 />
  </div>
  <div class="border-b-4">
    <Stairs />
  </div>

  <div class="border-b-4">
    <InnerTransformation />
  </div>

  <TeacherBio />
  <CTA />
</div>

<!-- <Stairs /> -->
<!-- <ClassStructure />
<Testimonials />
<ThreeSteps />
<WhatYouGet /> -->
