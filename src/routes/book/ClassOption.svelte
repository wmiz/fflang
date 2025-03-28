<script>
  export let classOption;
  export let btnColor;
  $: isFull = classOption.spots === 0;
</script>

<a href={classOption.link} class={isFull ? 'disabled' : ''}>
  <div class="relative bg-white rounded-xl shadow-md border-2 text-left md:p-8 p-6 flex flex-col justify-between text-center hover:scale-102 transition-transform duration-50 ease-in-out">
    <h3 class="text-xl font-semibold text-brand-secondary mb-3">Class Starts: {classOption.startDate}</h3>
    <p class="text-lg"><strong>Day:</strong> {classOption.day}</p>
    <p class="text-lg"><strong>Time (MST):</strong> {classOption.timeCST}</p>
    <p class="text-[#EE6352] text-lg font-bold">{classOption.spots} spots available ({classOption.spots}/{classOption.totalSpots})</p>
    {#if isFull}
      <div class="overlay">
        <div class="diagonal-text text-center font-bold drop-shadow">CLASS FULL</div>
      </div>
    {/if}
    <div class="mt-4">
      <p class="text-xl font-semibold">Price: <span class="line-through text-gray-500">${classOption.originalPrice}</span> <span class="text-[#1877F2]">${classOption.price}</span></p>
      <p>Save $100 - Limited Time Offer</p>
    </div>
    <button disabled={isFull} class="mt-4 shadow-lg text-xl text-white rounded-md hover:bg-brand-secondary font-bold py-6 px-8 m-auto btn w-full" style="background:{btnColor}">Enroll Now</button>
  </div>
</a>

<style>
  a.disabled {
    pointer-events: none;
    cursor: default;
  }

  .overlay {
    position: absolute;
    background-color: rgba(255, 255, 255, 0.5); /* Semi-transparent white */
    top: 0%;
    left: 0%;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 10; /* Ensures overlay is on top */
  }

  .diagonal-text {
    transform: rotate(-45deg);
    font-size: 2.5rem; /* Large text */
    background-color: white;
    border: solid 3px #EE6352; /* Border color */
    color: #EE6352;
    width: 100%;
    padding: 5px;
    color: #EE6352; /* Stands out against grey background */
    white-space: nowrap; /* Prevents text wrapping */
  }
</style>