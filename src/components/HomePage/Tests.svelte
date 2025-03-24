<script>
    // Define your testimonials array
    let testimonials = [
      { quote: "Great product!", author: "Alice" },
      { quote: "Amazing service!", author: "Bob" },
      { quote: "Highly recommend!", author: "Charlie" },
      { quote: "Great product!", author: "Alice" },
      { quote: "Amazing service!", author: "Bob" },
      { quote: "Highly recommend!", author: "Charlie" },
      { quote: "Great product!", author: "Alice" },
      { quote: "Amazing service!", author: "Bob" },
      { quote: "Highly recommend!", author: "Charlie" },
      { quote: "Great product!", author: "Alice" },
      { quote: "Amazing service!", author: "Bob" },
      { quote: "Highly recommend!", author: "Charlie" },
      // Add more testimonials as needed
    ];
  
    // Variables to store element widths for dynamic animation duration
    let scrollingContentWidth;
    let duration = 20; // Default duration in seconds
  
    // Reactive statement to calculate duration for consistent speed (e.g., 100px per second)
    $: if (scrollingContentWidth) {
      const speed = 100; // Pixels per second
      const distance = scrollingContentWidth / 2; // Distance to move (50% of total width)
      duration = distance / speed; // Adjust duration based on content width
    }
  </script>

<style>
    .container {
      width: 100%; /* Full width of the parent, adjust as needed */
    }
  
    .scrolling-content {
      display: flex; /* Arrange testimonials in a horizontal line */
      animation: scroll linear infinite; /* Apply animation */
    }
  
    .testimonial {
      flex: 0 0 auto; /* Prevent shrinking or growing */
      margin-right: 20px; /* Spacing between testimonials */
      white-space: nowrap; /* Keep text in one line */
    }
  
    /* Animation keyframes */
    @keyframes scroll {
      from {
        transform: translateX(0); /* Start at initial position */
      }
      to {
        transform: translateX(-50%); /* Move left by half the content width */
      }
    }
  </style>
  <div class="bg-white overflow-hidden">
    
  <div class="container w-full">
    <div class="scrolling-content" bind:clientWidth={scrollingContentWidth} style="animation-duration: {duration}s;">
      <!-- Render testimonials twice for seamless looping -->
      {#each testimonials as testimonial}
        <div class="testimonial">{testimonial.quote} - {testimonial.author}</div>
      {/each}
      {#each testimonials as testimonial}
        <div class="testimonial">{testimonial.quote} - {testimonial.author}</div>
      {/each}
    </div>
  </div>

</div>