<script>
  import ExpandableColumn from './ExpandableColumn.svelte';
  import door from "$lib/img/door.png";

  const column1 = [
    '<span class="font-bold">FACT:</span> Stories Generate <span class="underline">THINKING ABOUT WORDS AND GRAMMAR</span>. Drills are the perfect example of RIGHT IDEA (Repetition is the Key to Mastery), but the WRONG APPLICATION. The idea is that repeating words and phrases over and over again will lead to the habit of being able to speak fluently. The problem is that instead of training the student to actually Speak Spanish, drills train them to focus their attention on the individual words and the grammar used in the phrases they are repeating. The end result is that the student ends up with the Habit of THINKING ABOUT THE WORDS AND THE GRAMMAR USED IN THE PHRASES they have been mindlessly repeating.',
    'This causes the Conventional Drill Based Student to habitually get stuck in their head, worrying about whether they have the right words and/or the right grammar. It takes a long time to overcome this habit of getting stuck in the head, unless the student is thrown into a full immersion experience, such as having to live in a country for a month or two where they are forced to speak Spanish, but that way of doing full immersion is nowhere near as enjoyable as the Fast & Fun way of doing Full Immersion. On average, it takes 600 hours (an hour a day for 2-3 years) to achieve basic fluency using the Conventional Drill Based Method. <span class="font-bold">Conventional Drill Based Learning is the Slowest way to Spanish Fluency.</span>'
  ];

  const column2 = []; // Empty column

  const column3 = [
    '<span class="font-bold">FACT:</span> Stories train the Habit of <span class="underline">FLUENT COMMUNICATION IN FULL SENTENCES</span>. The Fast & Fun definition of “Spanish Fluency” is “Being in the Natural Flow of the Conversation as the Communication Flows from Sentence to Sentence.” When you think about it…a story is simply a SEQUENCE of sentences. Stories are the Key to Accelerated Fluency because they get the student Communicating in a SEQUENCE of full sentences right from the start. The Key is being able to effortlessly FLOW from sentence to sentence. If you can remember a story, you can remember entire chunks of Spanish communication…here’s why below.',
    'Years ago, there was a type of stage performer called a MEMORY MASTER. These MEMORY MASTERS were able to shock and amaze the audience by instantly memorizing any number of items chosen by the audience. Although it seemed like it, none of them had superhuman brains or memories. What they DID have is a system they called THE LINK SYSTEM. They knew that it\'s simply not possible to remember a list of individual items, so they devised a system to LINK them all together into a SEQUENCE.',
    'The most popular device for LINKING these random items together was a STORY. We use the exact same device, but instead of using a Story to Remember a list of random items, we use stories to help the student Remember a vast range of different sentence structures. As we have fun playing with and talking about different types of Stories, the student is unconsciously learning how to LINK the different types of sentences together in a natural and flowing way. This is How we Achieve Accelerated Fluency. We get the student <span class="underline">IN</span> the flow of the conversation in just 20 hours…over 8 weeks, when it takes Conventional Drill Based Learning 600 hours (an hour each day) over 2-3 years to achieve this same level of Basic Spanish Fluency. <span class="font-bold">Stories are by far the FASTEST WAY TO SPANISH FLUENCY.</span>'
  ];
</script>
  <div class="border-b-4 ">
<div class="flex flex-wrap m-20 items-center">
  <div class="w-full">
    <h2 class="text-6xl font-bold font-accent text-center mb-10">
      Door #3 = The Door to <span class="underline text-yellow-500">FASTER</span> Learning
    </h2>
  </div>
  <ExpandableColumn paragraphs={column1} />
  <div class="w-1/3">
    <img src={ door } alt="Column 2 Image" class="w-full h-auto" />
  </div>
  <ExpandableColumn paragraphs={column3} />
</div>
</div>
