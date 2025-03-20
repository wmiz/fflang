<script>
  import test1 from "$lib/img/test1.jpg";
  import test2 from "$lib/img/test2.jpg";
</script>

<div class="m-20 my-30 mb-30">
  <h2 class="text-6xl font-bold font-accent text-center mb-10">
    Testimionials
  </h2>
  <div class="my-10 flex">
    <div
      class="card text-center w-1/2 bg-white border-4 shadow-lg m-2 rounded-md"
    >
      <div class="card-body">
        <h2 class="card-title text-4xl font-accent mb-8">
          “All three said She is the best teacher they have ever had”
        </h2>
        <div class="flex flex-col gap-8 justify-center items-center">
          <img src={test1} width="300" class="" alt="" />
          <div class="text-left">
            <p class="text-xl mb-2">
              My children have thrived under her teaching, all three said she is
              the best teacher they have had because not only does she make it
              fun; they can also retain the information. She uses many different
              methods so even though my three kids learn differently they have
              all been able to learn at the same level of understanding. <span
                class="underline"
                >After class, they are laughing and all talking in Spanish</span
              >.
            </p>
            <p class="text-xl font-bold">- Sarah Golden (Homeschooling mom)</p>
          </div>
        </div>
      </div>
    </div>
    <div
      class="card text-center w-1/2 bg-white border-4 shadow-lg m-2 rounded-md"
    >
      <div class="card-body">
        <h2 class="card-title text-4xl font-accent mb-8">
          “I cannot say enough wonderful things about this class”
        </h2>
        <div class="flex flex-col gap-8 justify-center items-center">
          <img src={test2} width="300" class="" alt="" />
          <div class="text-left">
            <p class="text-xl mb-2">
              My son (14) and my daughter (11) took the Spanish foundational 1
              class from Senora and both loved the class. My son is shy and does
              not like class participation, but he finished every class smiling
              with stories about something that he enjoyed during class. <span
                class="underline"
                >I cannot say enough wonderful things about this class or Senora
                Goodey.</span
              > She genuinely enjoys teaching children and it shows."
            </p>
            <p class="text-xl font-bold">- Sarah Golden (Homeschooling mom)</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div>
    <button
      class="btn w-full text-white cursor-pointer bg-[#16455c] p-8 text-xl uppercase hover:underline"
      >More Testimionials</button
    >
  </div>
</div>
