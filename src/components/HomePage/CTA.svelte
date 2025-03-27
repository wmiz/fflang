<script>
  // Array of main program components with name, description, and value
  const mainComponents = [
    { name: "The 60 Minute Live Class", value: 400 },
    { name: "45 Min Pre-Recorded Booster Class", value: 240 },
    { name: "Garbanzo Story-based Interactive Fun App", value: 150 },
    { name: "Sr. Wooly Story-based Music Video App", value: 199 },
    { name: "Audio-Digital Novel Llama en Lima", value: 25 },
    { name: "Comprehensive Multi-Sensory Learning Package", value: 99 },
    { name: "5 Interactive Story Builders", value: 75 },
    { name: "Selection of Digital Vocab Games", value: 59 },
    { name: "Fun Interactive Song Sheets", value: 25 },
    { name: "Extra Zoom Boosters", value: 100 },
    { name: "Selection of More Mystery Bonus Material", value: 99 },
  ];

  // Calculate total value dynamically by summing the values of main components and bonuses
  const totalValue =
    mainComponents.reduce((sum, item) => sum + item.value, 0)

  // Define pricing variables
  const regularPrice = 297;
  const specialPrice = 197;
</script>

<div class="px-20">
  <h1 class="text-6xl font-accent font-bold mb-8 text-center ">
    My Goal with this Program…
  </h1>
  <p class="text-2xl mb-8">
    My Goal with this program is to give 10X the Value of the Price…Let’s see if
    I achieve it…Here’s what you get…
  </p>
  <section class="mb-8 shadow-2xl bg-white p-8 rounded-xl">
    <ul>
      {#each mainComponents as component, index}
        <li
          class="text-xl mb-2 rounded-lg flex items-center justify-between {index % 2 === 0
            ? 'bg-white'
            : 'bg-gray-100'}"
        >
          <strong class="text-3xl">
            <span class="text-[#EE6352] px-1">✔</span>
            {component.name}:
          </strong>
          <span class=" text-2xl text-[#1877F2] mr-2 font-bold"
            >Value = ${component.value}</span
          >
        </li>
      {/each}
    </ul>
  </section>

  <section class="text-4xl text-center font-accent mt-16">
    <p class=" text-[#EE6352] font-bold">
      Total Value = <span class="text-[#EE6352]">${totalValue.toFixed(2)}</span>
    </p>
    <p class="mb-4">(Not including the “Priceless” Inner Transformation)</p>
    <p class="font-bold">
      Originally, $297      

      <span class="text-4xl ml-2 font-bold text-blue-500">Now, Only $197</span>
    </p>
    <div class="text-center font-body py-8">
      <a href="/book">
        <button
          class="btn bg-[#EE6352] rounded-full bg-[#000000] text-white text-3xl p-8 uppercase shadow-lg hover:underline hover:scale-102 transition-transform duration-50 ease-in-out"
          >Book Now</button
        >
      </a>
    </div>
    <h3 class="text-center font-bold uppercase text-[#1877F2] text-5xl mb-8">Did I Reach my Goal?</h3>
    <p class="text-left mb-4 text-2xl">There it is…all laid out out. Did I reach my goal to give 10X the value? It all comes down to how much you value the Inner Transformation. Only you can decide.
    </p>
    <p class='text-left mb-10 text-2xl'>Hope to meet you and your child…and embark upon the next adventure together…with your child as one of the 8!
    </p>
  </section>
</div>
