<script>
    // Array of main program components with name, description, and value
    const mainComponents = [
        {
            name: "- The 60 Minute Live Class",
            description: "where we use the best Accelerated Learning Techniques in the World = Stories, Games, Music Props, Slides, Video clips, Movie-Talks, etc. and more…",
            value: 400
        },
        {
            name: "- 45 Minute Pre-Recorded Zoom Booster Video Class",
            description: "a whole new and different class which solidifies the Learnings from the Live class and doubles the Skill Level of the Live Class…",
            value: 240
        },
        {
            name: "- Garbanzo Story-Based Interactive Fun App",
            description: "this is the first of 3x15 minute Mini-Classes that make up the 3rd weekly Class. The “Garbanzo” App is only available to teachers, but now available to you…",
            value: 150
        },
        {
            name: "- Senor Wooly Story-based Music Video App (Hilarious Songs)",
            description: "our 2nd Mini-Class which uses our innate musical intelligence to boost skill levels and pull a huge number of new words into Long-Term Memory…also, only available to teachers…and now to you…",
            value: 199
        },
        {
            name: "- Audio-Digital Novel Llama en Lima",
            description: "Our 3rd Mini-Class audio-digital novel that enables us to fully establish the skill of reading while simultaneously building perfect pronunciation and massively boosting Vocabulary…",
            value: 25
        },
        {
            name: "- Comprehensive Multi-Sensory Learning Package",
            description: "including all class slides, individual movie-talk slides, digital interactive activities and much more…all easily searchable and organized…",
            value: 99
        }
    ];

    // Array of bonuses with name, description, and value
    const bonuses = [
        {
            name: "- 5 Interactive Story Builders",
            description: "that enable them to use their Creativity to take a story in multiple different directions according to their choice…",
            value: 75
        },
        {
            name: "- Selection of Digital Vocab Games",
            description: "fun games that massively expand Vocabulary as you play them…",
            value: 59
        },
        {
            name: "- Fun Interactive Song Sheets",
            description: "with the Song Videos all carefully chosen to integrate with weekly classes and thoroughly vetted to make sure they are all child-friendly…",
            value: 25
        },
        {
            name: "- Extra Zoom Boosters",
            description: "not essential, but there for those times when they are on a roll and their love for Spanish makes them hungry for more…",
            value: 100
        },
        {
            name: "- Selection of Mystery Bonus Material",
            description: "also for when they are on a roll and their love for Spanish makes them hungry for more. Students can select new bonus material to interact with each and every week…",
            value: 99
        }
    ];

    // Calculate total value dynamically by summing the values of main components and bonuses
    const totalValue = mainComponents.reduce((sum, item) => sum + item.value, 0) + 
                      bonuses.reduce((sum, item) => sum + item.value, 0);

    // Define pricing variables
    const regularPrice = 297;
    const specialPrice = 197;
</script>

<div class="mx-20">
    <!-- Main Heading -->
    <h1 class="text-7xl font-accent font-bold mb-12 text-center">Summary: Here’s What You Get…</h1>
    <!-- Main Program Components Section -->
    <section class="mb-8">
        <h2 class="text-6xl font-accent font-bold mb-4 underline">1. Main Program Components</h2>
        <ul>
            {#each mainComponents as component}
                <li class="text-2xl mb-2">
                    <strong class="text-4xl ">{component.name}:</strong> {component.description} 
                    <em class="font-bold text-accent">Value = ${component.value}</em>
                </li>
            {/each}
        </ul>
    </section>

    <!-- Bonuses Section -->
    <section class="mb-8">
        <h2 class="text-6xl font-accent font-bold mb-4 underline">2. Bonuses</h2>
        <ul>
            {#each bonuses as bonus}
                <li class="text-2xl mb-2">
                    <strong class="text-4xl">{bonus.name}</strong>: {bonus.description} 
                    <em class="font-bold text-red-500">Value = ${bonus.value}</em>
                </li>
            {/each}
        </ul>
    </section>

    <!-- Inner Transformation Section -->
    <section class="text-3xl font-bold mb-12">
        <h2 class="text-6xl font-accent font-bold mb-4 underline">3. Inner Transformation</h2>
        <p class="mb-2">How do you put a value on replacing false limiting beliefs from the broken school system with 3 Empowering beliefs…“I love Learning,” “Learning’s Easy for me,” “I’m a Fast Learner”?</p>
        <p class="mb-2">How do you put a value on completely restoring The Natural Love of Learning that the broken school system nearly destroyed and moving the overall value of learning in general up to the top of a values hierarchy?</p>
        <p class="mb-2">How do you put a value on helping a child remember they are a Child of God, a Unique expression of the Infinite with a Unique Gift inside of them…waiting to be drawn out (educe) and shared with the world?</p>
        <p class="mb-2">I cannot put a value on these Inner Benefits because to me… They’re Priceless, so I leave you to put your own value on these Bigger… More Important Benefits… than learning Spanish.</p>
    </section>

    <!-- Pricing Section -->
    <section class="text-6xl text-center font-accent">
        <p class="mb-8"><strong>Total Value = <span class="text-red-500">${totalValue.toFixed(2)}</span> (Not including the Inner Transformation because it’s priceless)</strong></p>
        <p><strong>Your Price = Only $<span class="underline">{regularPrice}</span>… Spring-Special Only <span class="text-7xl ml-2 text-accent">${specialPrice}</span></strong></p>
        <div class="text-center font-body py-12">
            <button class="btn bg-red-500 bg-[#16455c] text-white text-5xl p-10 w-1/2 uppercase shadow-lg hover:underline">Book Now</button>
          </div>
    </section>

    <section class="pb-8">
        <!-- <h2 class="text-6xl font-accent font-bold mb-4 underline">A Personal Note</h2> -->
        <div class="text-2xl italic text-[#16455c]">
            <p class="mb-2">* I live by the 10X Principle…which means I always do the best I can to give at least 10X the value of what I receive. Even though we can’t put a price on the Inner Transformation…I believe I am living up to my 10X Principle by keeping the price this low for as long as I can.</p>
            <p class="mb-2">If you are interested, I urge you to click the “Book Now” button and go straight to the class schedule page. You will see CLASS FULL in big red letters across the classes that already have 8 students, and you will see the number of spaces left (also in red) for spaces still available.</p>
            <p>I hope to meet your child in the next class!</p>
            <p>- Reed</p>
        </div>
    </section>
</div>
