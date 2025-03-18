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
  <div class="hero-content max-w-4/5 flex flex-col lg:flex-row lg:justify-between text-neutral-content px-4 lg:px-0 w-full relative z-10 lg:gap-20">
    <!-- Video Column -->

    <!-- Text Column -->
    <div class="w-full lg:w-1/2 lg:pl-8 font-body">
      <h1 class="text-7xl font-bold font-accent mb-6">
        Learn a Years Worth of Spanish in Just 8 Weeks
      </h1>
      <h1 class="text-5xl font-bold font-accent mb-6">
        With Zero Boring Drills!
      </h1>
      <p class="text-2xl mb-2">NEW Fast & Fun Accelerated 8-Week Spanish Program that has helped thousands of kids…(Age 11+)</p>
      <div class="flex gap-4 mt-6">
        <!-- <button class="btn btn-accent btn-xl">Enroll Now</button> -->
        <button class="btn btn-accent btn-xl w-1/2">Book Now</button>
      </div>
    </div>
  </div>
</div>
<div class="flex">
  <div class="w-1/3 bg-accent text-white text-center text-5xl py-4 font-accent">
    <h2>1. More Enjoyable Learning</h2>
  </div>
  <div class="w-1/3 bg-accent text-white text-center text-5xl py-4 font-accent">
    <h2>2. Easier Learning</h2>
  </div>
  <div class="w-1/3 bg-accent text-white text-center text-5xl py-4 font-accent">
    <h2>3. Faster Learning</h2>
  </div>
  <div></div>
  <div></div>
</div>