<script>
  import video from "$lib/video/vid.mp4";

  function toggleMute(event) {
    event.target.muted = !event.target.muted;
  }
</script>

<div class="flex justify-center items-center md:my-16 mt-8 md:px-10 px-4">
  <div class="flex justify-center items-center flex-col md:gap-12 gap-8">
    <h2 class="md:text-5xl text-3xl text-center font-accent font-bold">
      <span class="text-[#EE6352] hidden md:block">↓</span> Click to Hear What They’re Saying
      <span class="text-[#EE6352]">↓</span>
    </h2>
    <video
      on:click={toggleMute}
      class="w-full md:w-2/3 cursor-pointer shadow-xl mb-10"
      autoplay
      muted
      loop
      src={video}
    ></video>
  </div>
</div>
<div
  class="md:text-2xl text-lg md:mb-20 md:mx-10 md:shadow-2xl md:p-10 p-4 rounded-xl md:bg-white"
>
  <h2
    class="md:text-6xl text-3xl font-accent font-bold md:text-center md:mb-12 mb-4"
  >
    Why Stories Beat Drills <span class="underline">Every Time</span>
  </h2>
  <p class="md:mb-12 mb-6">
    Virtually every language program out there—whether it’s Duolingo, Rosetta
    Stone, classroom curricula, or even a well-meaning native speaker at your
    co-op—relies on drills. They promise fluency through endless word lists and
    grammar exercises, but it takes 600 hours and 2-3 years to reach even a
    basic level of Spanish fluency…and worse, <span class="">kids hate it.</span
    > Their boredom turns to frustration, then resistance, and learning grinds to
    a halt.
  </p>
  <p class="">
    <span class="md:text-3xl text-2xl font-bold"
      >This 8-week program (3 classes a week, 24 total) <span
        class="text-[#EE6352] italic">flips the script.</span
      ></span
    > From the very first class, we’re 100% in Spanish—not just words, but full conversations.
    We use stories instead of drills because stories make learning a joy, not a chore.
    Over 30 years as a language teacher and homeschooling mom myself, I’ve seen how
    this approach gets kids speaking fluently in just 20 hours. It’s designed for
    families like yours—those seeking a fast, effective, and engaging alternative
    to the old, broken way.
  </p>
  <!-- <p class="mb-12">
    This program is for Homeschooling Moms of pre-teens & teens who have pulled
    their kids out of the Broken School System and are <span
      class="font-bold underline">looking for a Better Way.</span
    >
  </p>
  <p>
    Virtually every program out there is <span class="underline font-bold">Drill Based</span>. They believe drilling
    endless lists of words and phrases enables the student to memorize the
    language. We use <span class="underline font-bold">Stories</span> instead of Drills and we created a Story
    (Metaphor): "<span class="underline font-bold">The 3 Doors to a Better Way</span>” to explain WHY.
  </p> -->
</div>
