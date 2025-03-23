<script>
    import door from "$lib/img/door.png";
    import ExpandableColumn from './ExpandableColumn.svelte';
  
    const column1 = [
      '<span class="font-bold">FACT:</span> Drills cause <span class="underline">BOREDOM, FRUSTRATION & RESISTANCE</span>. You don’t need to be an expert in Accelerated Learning to know these are the worst possible Learning States. All Learning is state dependent, and if the student is not in the Right State, there simply won’t be much learning going on. As a veteran teacher with 30 plus years experience…I can tell you with 100% Certainty…if your child is resistant to learning, <span class="underline">the problem is not your child. It’s the teaching method, and the broken school system it came from</span>.'
    ];
  
    const column3 = [
      '<span class="font-bold">FACT:</span> Stories Generate <span class="underline">CURIOSITY, PLAYFULNESS & ELEVATION</span>. A well-built story can generate the most effective learning states in the world. Accelerated learning researchers tested every known emotional state to find out which are the most effective learning states. They found the 3 best states for Accelerated learning are <span class="font-bold">Curiosity and Surprise…Playfulness and Humor…and the State of Elevation.</span> Elevation is when we are lifted up to a Higher Level of Functioning by stories about <span class="underline">MORAL BEAUTY</span>. You don’t have to be an Accelerated Learning Expert to know that Curiosity is a better learning state than Boredom…Playfulness is a better learning state than frustration…and Elevation is a better learning State than Resistance.'
    ];
  </script>
  
  <div class="border-y-4  bg-gray-100">
    <div class="flex flex-wrap m-20 mb-20 items-center">
        <div class="w-full">
        <h2 class="text-6xl font-bold font-accent text-center mb-16">
            Door #1 = The Door to <span class="underline text-yellow-500">More ENJOYABLE</span> Learning
        </h2>
        </div>
        <ExpandableColumn paragraphs={column1} header="PROBLEM" />
        <div class="w-1/3 p-8">
        <img src={door} alt="Door to More Enjoyable Learning" class="w-full h-auto p-20" />
        </div>
        <ExpandableColumn paragraphs={column3} header="SOLUTION" />
    </div>
</div>