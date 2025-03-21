<script>
  import herobg from "$lib/img/hero.png";
</script>

<div class="p-10 min-h-screen relative" style="background: white">
  <!-- Add a radial mask -->
  <div
    class="absolute inset-0 bg-white text-black"
    style="
      <!-- background: radial-gradient(circle, transparent 60%, rgba(0, 0, 0, 0.5) 100%); -->
    "
  ></div>

  <!-- Content overlay -->
  <div class="hero-overlay"></div>
  <div
    class="flex flex-col lg:justify-between text-neutral-content px-4 lg:px-0 w-full relative z-10 lg:gap-0"
  >
    <!-- Video Column -->

    <!-- Text Column -->
    <div class="w-full lg:pl-8 font-body rounded-xl p-8 pb-0 text-black">
      <!-- <p class="text-2xl mb-6">
          NEW Fast & Fun Accelerated 8-Week Spanish Program that has helped
          thousands of kids…(Age 11+)
        </p> -->

      <p class="mb-2 text-3xl text-[#e4492d] font-bold drop-shadow-md">
        NEW Fast & Fun Accelerated 8-Week Spanish Program that has helped
        thousands of kids… (Age 11+)
      </p>
      <h1 class="text-7xl text-[#1877F2] font-bold font-accent mb-4">
        Speak Better Spanish in 8-Weeks than <span class="underline"
          >2-3 years</span
        > of Conventional Drill-Based Learning…
      </h1>
      <p class="text-3xl mb-2">
        And Get… A <span class="font-bold">World Language Credit</span> Certificate to meet the language
        requirement for Graduation or College Entry
      </p>
      <div class="flex gap-4 my-6">
        <!-- <button class="btn btn-accent btn-xl">Enroll Now</button> -->

        <button
          class="btn bg-[#e4492d] text-white border-none text-2xl p-6 rounded-full min-w-[240px]"
          >Book Now</button
        >
      </div>
      <div class="max-w-1/2 text-2xl">
        <p class="mb-2">
          This NEW Story-based way of teaching that makes learning more
          enjoyable, easier, and much faster than conventional Drill-based
          learning.
        </p>
        <p class="mb-2">
          We have an 8-Week program with 3 classes a week…with a total of 24
          classes over 8 weeks…and <span class="font-bold">100% of every class is IN SPANISH</span> and not
          just IN spanish, BUT IN <span class="font-bold">SPANISH CONVERSATION.</span>
        </p>
        <p><span class="underline">We use stories to teach SPANISH, instead of drills</span> because stories enable us to spend 100% of our time IN SPANISH CONVERSATION. 
        </p>
      </div>
    </div>
    <p>
      The Fast & Fun 8-Week Accelerated Spanish Program gets students
      communicating IN Spanish…IN full sentences right from the start. It trains
      students to be in THE NATURAL FLOW OF THE CONVERSATION rather than getting
      stuck in their head thinking about words & grammar while the conversation
      leaves them behind.
    </p>

    <div class="w-full flex justify-end mt-[-360px]">
      <img src={herobg} width="600" alt="Live Cam" />
    </div>
  </div>
</div>
<div class="flex font-bold">
  <div
    class="w-1/3 bg-[#e4492d] text-white text-center text-2xl py-4 font-accent"
  >
    <h2 class="text-center">More Enjoyable Learning</h2>
  </div>
  <div
    class="w-1/3 bg-[#e4492d] text-white text-center text-2xl py-4 font-accent"
  >
    <h2 class="">Easier Learning</h2>
  </div>
  <div
    class="w-1/3 bg-[#e4492d] text-white text-center text-2xl py-4 font-accent"
  >
    <h2 class="text-center">Faster Learning</h2>
  </div>
</div>
