<script>
  import live from "$lib/img/live.png";
  import zoom from "$lib/img/zoom.png";
  import triple from "$lib/img/triple.png";

  import Card from "./Card.svelte";

  const class1Description =
    "A lively, action-packed hour on Zoom—props, music, games, and stories, all in Spanish. No English, no stress—just fun and full participation. Limited to 8 students, I set the week’s learning anchors here.";
  const class2Description =
    "A pre-recorded class to double the live session’s skills, watchable whenever fits your schedule. It’s flexible and packed with fresh material to push fluency further.";
  const class3Description =
    "Three 15-minute mini-classes using multisensory apps kids love—Garbanzo for vocab, Señor Wooly for music and skills, and Llama en Lima for reading and pronunciation. These lock in the week’s high-frequency structures.";
</script>

<div class="m-10 my-30 mb-10">
  <h2 class="text-6xl font-bold font-accent text-left mb-4 text-[#1877F2]">
    How It Works: <span class="underline">3 Classes a Week</span>
  </h2>
  <div class="text-2xl mb-12">
    <p class="text-2xl">
      <span class="font-bold text-3xl">Our program is simple but powerful</span> 3 classes a week for 8 weeks, totaling
      24 classes. Each class builds on the last, taking your child from absolute
      beginner to conversational fluency.
    </p>
    <!-- <p>
        Eventually, I developed the Story-Key™ Method…the method I have used to
        help thousands Learn Spanish in a Quick, Easy and Enjoyable way. The Fast
        & Fun 8-Week Accelerated Spanish Program is what happened when I put it
        all together. The Student does 3 Different Classes a week, each with its
        own special range of fun Accelerated Learning Activities. Here’s what it
        looks like…
      </p> -->
  </div>
  <div class="flex justify-around gap-6">
    <Card
      title="Class 1"
      imageSrc={live}
      subtitle="Live Zoom"
      duration="(60 min)"
      description={class1Description}
    />
    <Card
      title="Class 2"
      imageSrc={zoom}
      subtitle="Booster"
      duration="(45 min)"
      description={class2Description}
    />
    <Card
      title="Class 3"
      imageSrc={triple}
      subtitle="Expansion"
      duration="(45 min)"
      description={class3Description}
    />
  </div>
</div>
