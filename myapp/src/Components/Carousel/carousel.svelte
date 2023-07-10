<script>
  let activeIndex = 2;
  const images = [
    "purple-bmw.PNG",
    "gold-bmw.PNG",
    "blue-bmw.png",
    "green-bmw.PNG",
    "red-bmw.PNG",
  ];

  function setActiveIndex(index) {
    activeIndex = index;
  }
</script>
<div class="carousel-wrapper">
  <p class="brand">BMW M8</p>
  <p class="choose">Choose a car color</p>
  


<div class="carousel">

  <h1 class="configur">CONFIGUR</h1>

  {#each images as image, index}
    {#if index === activeIndex}
      <img class="carousel-image" src={image} alt="Carousel Image" />
    {/if}
  {/each}

</div>




<div class="carousel-indicators">
  {#each images as _, index}
    <div class="indicator-container">
      <div
        class="indicator {index === activeIndex ? 'active' : ''} {index === 0
          ? 'mor'
          : index === 1
          ? 'gold'
          : index === 2
          ? 'mavi'
          : index === 3
          ? 'yesil'
          : 'kirmizi'}"
        on:click={() => setActiveIndex(index)}
      />
    </div>
  {/each}

  
</div>
<div class="price">
  <p class="total">Total</p>
  <p class="pay">$ 70.000</p>
  <button>Accept</button>
  </div>

</div>

<style>
  .carousel-wrapper{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    padding: 2rem;
  }
  .brand{
    color: white;
    font-size: 1rem;
    font-weight: 100;
  }
  .choose{
    color: white;
    font-size: 1.5rem;
    font-weight: 400;
  }
  .configur{
    z-index: 1;
    position: absolute;
    top:-3rem;
    font-size: 10rem;
    color: #26363b;
    background-color: transparent;
  }
  .carousel {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 400px;
    padding: 2rem;
    position: relative;
    
   
  }

  .carousel-image {
    background-color: transparent;
    width: 60rem;
    object-fit: cover;
    z-index: 999;
   
  }

  .price{
    display: flex;
    flex-direction: column;
    gap:0.5rem;
    margin-left: 80%;
    margin-top: -3rem;
    
  }
  .total{
    color: #a7aeb1;
    font-weight: 400;
  }
  .pay{
    color: white;
    font-size: 1.2rem;
  }
  .price> button{
    padding: 5px;
    background-color: #ffc700;
    border-radius: 10px;
    border: none;
    cursor: pointer;
  }

  .carousel-indicators {
    display: flex;
    justify-content: center;
    margin-top: 20px;
    gap: 1rem;
  }

  .indicator-container {
    display: flex;
    align-items: center;
  }

  .indicator {
    width: 25px;
    height: 25px;
    border-radius: 50%;
    margin: 0 5px;
    cursor: pointer;
    background-color: gray;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    
  }

  .indicator.active {
    background-color: mavi;
  }

  .indicator.mor {
    background-color: blueviolet;
  }

  .indicator.gold {
    background-color: #ada556;
  }

  .indicator.mavi {
    background-color: blue;
  }

  .indicator.yesil {
    background-color: green;
  }

  .indicator.kirmizi {
    background-color: red;
  }

  .indicator.active::before {
    content: "";
    width: 130%;
    height: 130%;
    border-radius: 50%;
    border: 2px solid gray;
    position: absolute;
    pointer-events: none;
  }
</style>
