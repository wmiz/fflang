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
  <div class="hero-content max-w-4/5 flex flex-col lg:flex-row-reverse lg:justify-between text-neutral-content px-4 lg:px-0 w-full relative z-10 lg:gap-20">
    <!-- Video Column -->
    <div class="w-full lg:w-1/2">
      <div class="relative w-full rounded shadow-2xl" style="padding-top: 56.25%;"> <!-- Responsive container -->
        <iframe
          class="absolute inset-0 w-full h-full rounded-lg shadow-2xl"
          src="https://www.youtube.com/embed/dQw4w9WgXcQ"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <!-- Text Column -->
    <div class="w-full lg:w-1/2 lg:pl-8 font-body">
      <h1 class="text-7xl font-bold font-accent mb-12">
        Learn 1-2 Years of High School Spanish in Just 8 Weeks...
      </h1>
      <p class="py-6 text-xl">
        The Fast And Fun Language program is an accelerated Spanish program which enables students to learn the equivalent of 1-2 years of high school Spanish in only 8 weeks. After completing an 8 week class, students receive a World language credit certificate that counts as a years worth of daily classroom Spanish.
      </p>
      <div class="flex gap-4 mt-6">
        <!-- <button class="btn btn-accent btn-xl">Enroll Now</button> -->
        <button class="btn btn-accent btn-xl w-1/2">Enroll Now</button>
        <button class="btn btn-white btn-xl w-1/2">Learn More</button>

      </div>
    </div>
  </div>
</div>
