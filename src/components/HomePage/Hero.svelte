<script>
  import herobg from "$lib/img/hero.jpg";
</script>

<div class="p-10 min-h-screen relative ">
  <!-- Add a radial mask -->
  <div
    class="absolute inset-0 bg-white text-black "
    style="
      <!-- background: radial-gradient(circle, transparent 60%, rgba(0, 0, 0, 0.5) 100%); -->
    "
  ></div>

  <div class="hero-overlay"></div>
  <div
    class="flex flex-col lg:justify-between text-neutral-content px-4 lg:px-0 w-full relative z-10 lg:gap-0"
  >
    <div class="w-full lg:pl-8 font-body rounded-xl p-8 pb-0 text-black">

      <p class="mb-2 text-3xl text-[#e4492d] font-bold drop-shadow-md">
        NEW Story-Based 8-Week Accelerated Spanish Program that has helped <span class="text-5xl uppercase">thousands</span> of kids (Age 11+)...      </p>
      <h1 class="text-6xl text-[#1877F2] font-bold font-accent mb-4">
        Speak Conversational Spanish in <span class="text-6xl">2 Months</span> instead of <span class="text-6xl">2 Years</span>...with Zero Boring Drills or Textbooks
      </h1>
      <p class="text-3xl mb-2">
        And Get… A <span class="font-bold text-4xl">World Language Credit</span> Certificate to meet the language
        requirement for Graduation or College Entry
      </p>
      <div class="flex gap-4 my-6">
        <!-- <button class="btn btn-accent btn-xl">Enroll Now</button> -->

        <button
          class="btn bg-[#e4492d] text-white border-none text-2xl p-6 rounded-full min-w-[240px]"
          >Book Now</button
        >
      </div>
      <div class="max-w-1/2 text-2xl mt-18">
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


    <div class="w-full flex justify-end mt-[-300px]">
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
