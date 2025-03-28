<script>
  export let classOption;
  $: isFull = classOption.spots === 0;
</script>

<a href={classOption.link} class={isFull ? 'disabled' : ''}>
  <div class="relative bg-white rounded-xl shadow-lgs md:p-8 p-6 flex flex-col justify-between text-center hover:scale-102 transition-transform duration-50 ease-in-out">
    <h3 class="text-2xl font-semibold text-brand-secondary mb-3">Class Starts: {classOption.startDate}</h3>
    <p class="text-xl"><strong>Day:</strong> {classOption.day}</p>
    <p class="text-xl"><strong>Time (MST):</strong> {classOption.timeCST}</p>
    <p class="text-[#1877F2] text-xl font-bold">{classOption.spots} spots available ({classOption.spots}/{classOption.totalSpots})</p>
    <div class="mt-4">
      <p class="text-xl font-semibold">Price: <span class="line-through text-gray-500">${classOption.originalPrice}</span> <span>${classOption.price}</span></p>
      <p>Save $100 - Limited Time Offer</p>
    </div>
    {#if isFull}
    <button disabledc={isFull} class="mt-4 text-3xl bg-white text-[#EE6352] rounded-full hover:bg-brand-secondary uppercase font-bold py-2 rotate-[-10deg] m-auto">Class Full</button>
    {:else}
    <button disabled={isFull} class="mt-4 shadow-lg text-xl bg-[#1877F2] text-white rounded-full hover:bg-brand-secondary font-bold py-6 px-8 m-auto btn">Enroll Now</button>
    {/if}
  </div>
</a>

<style>
  a.disabled {
    pointer-events: none;
    cursor: default;
  }

  .overlay {
    position: absolute;
    top: 30%;
    left: 0%;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 10; /* Ensures overlay is on top */
  }

  .diagonal-text {
    /* transform: rotate(-10deg); */
    font-size: 4rem; /* Large text */
    background-color: #EE6352;
    width: 100%;
    padding: 5px 10%; /* Padding for better visibility */
    color: white; /* Stands out against grey background */
    white-space: nowrap; /* Prevents text wrapping */
  }
</style>