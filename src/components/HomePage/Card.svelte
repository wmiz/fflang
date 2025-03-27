<script>
    export let title;
    export let imageSrc;
    export let subtitle;
    export let duration;
    export let description;
  </script>
  
  <div class="card text-center bg-white w-1/3 shadow-2xl rounded-md bg-white">
    <div class="card-body flex-none p-8 text-left">
      <h2 class="card-title justify-center p-2 rounded-lg text-4xl font-accent mb-2 uppercase bg-[#EE6352] shadow-md text-white w-full">{title}</h2>
      <img src={imageSrc} width="80" class="m-auto mb-2" alt="" />
      <h2 class="card-title m-auto text-3xl font-accent italic">{subtitle}</h2>
      <p class="text-xl font-bold text-center">{duration}</p>
      <p class="text-xl text-center">{@html description}</p>
    </div>
  </div>