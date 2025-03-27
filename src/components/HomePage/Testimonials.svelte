<script>
  import test1 from "$lib/img/test1.jpg";
  import test2 from "$lib/img/test2.jpg";
</script>

<div class="m-10 my-30 mb-20">
  <!-- <hr class="text-gray-300"> -->
  <div class="my-10 flex gap-6">
    <div class="card text-left w-1/2 bg-white shadow-2xl rounded-md ">
      <div class="card-body">
        <h2 class="card-title text-4xl font-accent mb-4 block">
          “All three said she is the <span class="text-[#EE6352] italic text-4xl">BEST</span> teacher they have ever had...”
        </h2>
        <div class="flex flex-col gap-8 justify-center items-center">
          <img
            src={test1}
            width="300"
            class="rounded-lg shadow-xl aspect-square object-cover"
            alt=""
          />
          <div class="text-left">
            <p class="text-xl mb-2">
              My children have thrived under her teaching, all three said she is
              the best teacher they have had because not only does she make it
              fun; they can also retain the information. She uses many different
              methods so even though my three kids learn differently they have
              all been able to learn at the same level of understanding. <highlight class="bg-yellow-200 px-1">After class, they are laughing and all talking in Spanish.</highlight
              >
            </p>
            <p class="text-2xl text-right font-bold">- Sarah Golden (Homeschooling mom)</p>
          </div>
        </div>
      </div>
    </div>
    <div class="card text-left w-1/2 bg-white shadow-2xl rounded-md">
      <div class="card-body">
        <h2 class="card-title text-4xl font-accent mb-4 block">
          “I cannot say enough <span class="text-[#EE6352] italic text-4xl">WONDERFUL</span> things about this class...”
        </h2>
        <div class="flex flex-col gap-8 justify-center items-center">
          <img
            src={test2}
            width="300"
            class="rounded-lg shadow-xl aspect-square object-cover"
            alt=""
          />
          <div class="text-left">
            <p class="text-xl mb-2">
              My son (14) and my daughter (11) took the Spanish foundational 1
              class from Senora and both loved the class. My son is shy and does
              not like class participation, but he finished every class smiling
              with stories about something that he enjoyed during class. <highlight class="bg-yellow-200 px-1">I cannot say enough wonderful things about this class or Senora
                Goodey.</highlight> She genuinely enjoys teaching children and it shows."
            </p>
            <p class="text-2xl text-right font-bold">- Connie Cupp (Homeschooling mom)</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="text-center">
    <a href="/testimonials">
      <button
        class="btn rounded-full text-white cursor-pointer bg-[#1877F2] shadow-xl p-6 text-xl uppercase hover:underline"
        >View More</button
      >
    </a>
  </div>
</div>
