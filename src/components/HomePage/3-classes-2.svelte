<script>
  import BookNow from "./BookNow.svelte";

  import llama from "$lib/img/llama.jpg";
  import senorwooly from "$lib/img/senorwooly.png";
  import garbanzo from "$lib/img/garbanzo.png";
</script>

<div class="m-20 my-30 mt-0 mb-20">
  <div class="my-10 mt-0 flex">
    <div
      class="card text-center w-1/3 bg-white shadow-2xl m-2 rounded-md"
    >
      <div class="card-body">
        <h2 class="card-title m-auto text-6xl font-accent mb-2">1st Mini-Class</h2>
        <!-- <img
          src={garbanzo}
          width="300"
          class="m-auto"
          alt=""
        /> -->
        <h2 class="card-title m-auto text-3xl font-accent mb-2">
            Garbanzo
        </h2>

        <p class="text-xl">
          Each Garbanzo is 5 minutes long, therefore 3 Garbanzos make up a
          Mini-Class. A 5 minute Garbanzo builds enormous familiarity with the
          targeted High Frequency Structures for each 3-Class set in a
          ridiculously small amount of time. It’s amazing how many words a
          single Garbanzo can pull into Long-Term memory in just 5 minutes, all
          while the student is enjoying a new fun activity. Kids love them
          because they build a progressive sense of confidence and some of them
          are absolutely hilarious, which boosts the playfulness and humor to
          another level.
        </p>
      </div>
    </div>
    <div
      class="card text-center w-1/3 bg-white shadow-2xl m-2 rounded-md"
    >
      <div class="card-body">
        <h2 class="card-title m-auto text-6xl font-accent mb-2">2nd Mini-Class</h2>
        <!-- <img
          src={senorwooly}
          width="300"
          class="m-auto mb-2"
          alt=""
        /> -->

        <h2 class="card-title m-auto text-3xl font-accent mb-2">
            Senor Wooly
        </h2>
        <p class="text-xl">
            Senor Wooly is a wonderful 15 Minute Story-Based Music Video Application that boosts listening, reading, and speaking skills all at the same time. Students find themselves unconsciously singing along with the words of the song as they answer questions about each verse of the song. It’s an innovative new way of using our innate musical intelligence to boost skill levels while pulling in a huge number of new words into Long-Term memory. The songs are original, always clean, and hilariously funny. Each song practices and builds upon the High Frequency Structures that we are targeting in each 3-Class Set.
        </p>
      </div>
    </div>
    <div
      class="card text-center bg-white w-1/3 shadow-2xl m-2 rounded-md"
    >
      <div class="card-body">
        <h2 class="card-title m-auto text-6xl font-accent mb-2">3rd Mini-Class</h2>
        <!-- <img
          src={llama}
          width="300"
          class="m-auto mb-2"
          alt=""
        /> -->
        <h2 class="card-title m-auto text-3xl font-accent mb-2">
            Audio-Digital Novel
        </h2>
        <p class="text-xl">
            <span class="italic">Llama en Lima</span> is a colorful and enjoyable audio-digital novel that enables us to fully establish the skill of reading while simultaneously building perfect pronunciation. Just like any novel, it massively builds vocabulary, but in this case, all of the words are going into Long-Term Memory because they are hooked onto the targeted <span class="font-bold">High Frequency Structures.</span> The novel has pictures and is about a llama from Lima, Peru and his adventures in the city. As the student reads while simultaneously listening to the audio, they unconsciously and automatically develop perfect pronunciation for all of the targeted <span class="font-bold">High Frequency Structures.</span> Each of the 7 chapters is perfectly synchronized with each 3-Class Set and its Mastery Level as we go through the 8-Week Program.
        </p>
      </div>
    </div>
  </div>
  <BookNow />
</div>
