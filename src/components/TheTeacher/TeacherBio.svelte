<script>
  import reed from "$lib/img/reed_green.jpg";
  import Title from "./Title.svelte"
  import Paragraph from "./Paragraph.svelte"
</script>

<div class="mx-auto ">
  <h2 class="text-5xl font-bold font-accent text-let mb-8">
    Hello, I’m Reed Goodey!
  </h2>
  <p class="mb-8 text-2xl">
    I’m a credentialed teacher with over 30 years of experience, including
    homeschooling my own kids. With degrees in French and Spanish
    Literature, a Master’s in Education, and fluency in Italian, I’ve taught
    all levels of Spanish and French—AP and International Baccalaureate
    included. My travels across Europe, Northern Africa, China, the Middle
    East, Mexico, and Central and South America have deepened my love for
    full-immersion learning.
  </p>
  <div class="relative">
    <img
      src={reed}
      width="400"
      height="400"
      alt="Reed's Journey"
      class="w-full md:w-1/3 md:float-left md:mr-8 md:mb-4 rounded-lg shadow-lg"
    />
    <div class="text-xl">
      <!-- First 3 paragraphs (always visible) -->
      
      <Title title={"Learning Should Inspire Joy"} />
      <Paragraph paragraph={"Forget dull drills—I believe learning should be fun…a truth proven over decades. I’ve watched thousands of students master languages 10 times faster than with conventional methods. The secret? Curiosity. When kids are curious, they absorb everything like sponges, and I’ve made that the heart of my teaching."} />

      <Title title={"A Revolution for Homeschoolers"} />
      <Paragraph paragraph={"Like John Taylor Gatto, I reject the broken system that stifles kids. That’s why I’ve specialized in helping homeschooling moms just like you meet world language requirements with my 8-Week Accelerated Spanish Program—the most effective I’ve ever seen. It blends a lifetime of techniques into a synergy that delivers 1-2 years of classroom Spanish in just 8 weeks."} />

      <Title title={"A Program Built for Your Child"} />
      <Paragraph paragraph={"Picture props, movement, and playful pauses sparking intense curiosity. My program layers mastery week by week, mixing modern innovation with timeless wisdom from pioneers such as Charlotte Mason. At the end, your child earns a World Language Credit Certificate for graduation or college—proof of their triumph."} />
    
      <Title title={"A Safe Space to Shine"} />
      <Paragraph paragraph={"Every class radiates lighthearted ease and humor, creating a safe haven where students relax, connect, and take risks in Spanish. With only 8 students per class, I tailor each moment to their needs, uncovering who they are beneath the surface."} />

      <Title title={"Your Child’s Adventure Awaits"} />
      <Paragraph paragraph={"Homeschooling mom, this isn’t just about Spanish—it’s about igniting your child’s potential. I can’t wait to know you both and to dive into this life-giving journey together."} />

      <Title title={"With Love, Reed"} />
      <Paragraph paragraph={"Join me, and let’s unlock a world of wonder for your child—one joyful lesson at a time."} />
      <Paragraph paragraph={"Reed"} />
    
    
    </div>
  </div>
</div>
