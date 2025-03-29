<script>
  import Testimonial from "./Testimonial.svelte";

  const testimonials = [
    {
      text: "I've been amazed at what they've been able to say and understand in Spanish after only a few weeks!",
      author: "Emily Heilman (Homeschooling mom)"
    },
    {
      text: "I can actually say I can read, write, and speak in a spontaneous way!",
      author: "Abby W. (age 16) Student"
    },
    {
      text: "I feel confident to hold a conversation with anyone in Spanish.",
      author: "Kolby D. (age 16) Student"
    },
    {
      text: "It’s not drills, rather it’s all verbal and it works, it really does.",
      author: "William G. (age 14) Student"
    },
    {
      text: "I have been absolutely astonished by how quickly my daughter has picked up on the language. This is the way languages should be taught!",
      author: "Tabitha S. (Homeschooling mom)"
    },
    {
      text: "My son has never been so inspired to learn before!",
      author: "Debra D. (Homeschooling mom)"
    },
    {
      text: "You can study books and rules and never be able to have a conversation, Reed is teaching them conversation from the beginning.",
      author: "Camila Whitman (Homeschooling mom)"
    }
  ];

  // Duplicate the testimonials for a seamless loop
  const allTestimonials = [...testimonials, ...testimonials];
</script>

<div class="marquee">
  <div class="marquee-content py-5">
    {#each allTestimonials as testimonial, i (i)}
      <div class="testimonial-wrapper">
        <Testimonial text={testimonial.text} author={testimonial.author} />
      </div>
    {/each}
  </div>
</div>

<style>
  /* Container that hides overflowing content */
  .marquee {
    overflow: hidden;
    position: relative;
    width: 100%;
    background-color: white;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }

  /* The scrolling container */
  .marquee-content {
    display: flex;
    width: max-content;
    animation: scroll 60s linear infinite;
  }

  /* Set a fixed width for each slide and adjust spacing */
  .testimonial-wrapper {
    width: 40vw; /* Adjust width as desired */
    margin-right: 2rem;
  }

  /* Keyframes animation: move left continuously */
  @keyframes scroll {
    from {
      transform: translateX(0);
    }
    to {
      transform: translateX(-50%);
    }
  }
</style>
