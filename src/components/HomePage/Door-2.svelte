<script>
  import door from "$lib/img/door.png";
  import ExpandableColumn from './ExpandableColumn.svelte';
  
    const column1 = [
      '<span class="font-bold">FACT:</span> Drills put the Language in <span class="underline">SHORT-TERM MEMORY</span>. The thinking behind drills is that if you repeat a list of words and phrases enough times, they will stick. And…Drills <span class="underline">DO</span> get Spanish words and phrases to eventually stick, but only for 3-4 weeks…just long enough to pass an exam…and then they are gone forever. Half of the moms I know took 2-3 years of Spanish in high school, but when I playfully speak to them in Spanish, they can’t remember any of it. WHY? Because drills only put the language into Short-Term Memory.',
      'Think of the mind like a giant iceberg…the Conscious Mind is the 5% you see above the surface and the powerful Unconscious Mind is the 95% that\'s below the surface where Mastery (Unconscious Competence) lives. The Conscious Mind processes logic, reason and Lists (of words). The Conscious Mind is also where Short-Term Memory lives.  Drilling lists of words and phrases is the logical approach to learning a language but this logical approach, because it appeals to the Conscious Mind, can only put those words and phrases into Short-Term Memory.',
      'Drills are the most difficult way to learn a language because as you drill more and more new words, you have to continue to drill the ones you have already drilled just to keep them. Eventually the workload builds up to the point where it becomes too difficult to keep going. <span class="font-bold">Conventional Drill-based learning is the most difficult way to learn any Language.</span>'
    ];
  
    const column2 = []; // Empty column
  
    const column3 = [
      '<span class="font-bold">FACT:</span> Stories put the Language in <span class="underline">LONG-TERM MEMORY</span>. Just like Short-Term Memory lives in the little conscious mind where logic and reason is processed…so, too, Long-Term Memory lives in the Unconscious Mind where emotion and meaning is processed. It is the emotional engagement a story generates that enables us to put all of the words and sentences that a story is built from straight into Long-Term Memory. Stories are the Key that opens the door to Long-Term Memory because stories naturally engage emotion.',
      'Our goal is Mastery…also known as “Unconscious Competence.” Unconscious Competence means being in the natural flow of a conversation without having to think about words or their meanings. It\'s much easier to build unconscious competence with the language in Long-Term Memory because we are already in the realm of the “Unconscious Mind.”',
      'The really good news is this…with the language going into Long-Term Memory, normal conversation in class over the 8-Week Program is more than enough repetition to give unconscious competence…AKA, Mastery. Even better news…Mastery of the Spanish language will always be there anytime you need it for the rest of your life…without having to reinforce any of it with boring drills. <span class="font-bold">The New Story Based Method is the EASIEST way to Learn Spanish.</span>'
    ];
  </script>
    <div class="border-b-4 bg-gray-100">
  <div class="flex flex-wrap m-20 my-10 items-center">
    <div class="w-full">
      <h2 class="text-7xl font-bold font-accent text-center mb-10">
        Door #2 = The Door to <span class="underline text-accent">EASIER</span> Learning
      </h2>
    </div>
    <ExpandableColumn paragraphs={column1} />
    <div class="w-1/3 p-8">
        <img src="https://placehold.co/400x600" alt="Column 2 Image" class="w-full h-auto" />
      </div>
    <ExpandableColumn paragraphs={column3} />
  </div>
</div>