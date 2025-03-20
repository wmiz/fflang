<script>
  import herobg from "$lib/img/hero.png";
</script>

<div
  class="hero min-h-screen relative"
  style="background-image: url({herobg}); background-size: cover; background-position: center;"
>
  <!-- Add a radial mask -->
  <div
    class="absolute inset-0"
    style="
      background: radial-gradient(circle, transparent 60%, rgba(0, 0, 0, 0.5) 100%);
    "
  ></div>

  <!-- Content overlay -->
  <div class="hero-overlay"></div>
  <div
    class="hero-content max-w-4/5 flex flex-col lg:flex-row lg:justify-between text-neutral-content px-4 lg:px-0 w-full relative z-10 lg:gap-20"
  >
    <!-- Video Column -->

    <!-- Text Column -->
    <div class="w-full lg:w-1/2 lg:pl-8 font-body">
        <!-- <p class="text-3xl mb-6">
          NEW Fast & Fun Accelerated 8-Week Spanish Program that has helped
          thousands of kids…(Age 11+)
        </p> -->

      <h1 class="text-7xl font-bold font-accent mb-6">
        Speak Better Spanish in 8-Weeks than <span class="underline"
          >2-3 years</span
        > of Conventional Drill-Based Learning…
      </h1>
      <p class="text-3xl mb-2">
        And Get… A World Language Credit Certificate to meet the language
        requirement for Graduation or College Entry
      </p>
      <div class="flex gap-4 my-6">
        <!-- <button class="btn btn-accent btn-xl">Enroll Now</button> -->
         
        <button class="btn btn-accent uppercase text-2xl p-8 w-1/2"
          >Book Now</button
        >
      </div>
     
    </div>
  </div>
</div>
<div class="flex">
  <div class="w-1/3 bg-accent text-white text-center text-5xl py-4 font-accent">
    <h2 class="text-right underline">1. More Enjoyable Learning</h2>
  </div>
  <div class="w-1/3 bg-accent text-white text-center text-5xl py-4 font-accent">
    <h2 class="underline">2. Easier Learning</h2>
  </div>
  <div class="w-1/3 bg-accent text-white text-center text-5xl py-4 font-accent">
    <h2 class="text-left underline">3. Faster Learning</h2>
  </div>
</div>
