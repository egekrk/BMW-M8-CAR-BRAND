<script>
  
</script>

<div class="hero-wrapper">
  <div class="top-content">
    <img src="bmw-logo.png" alt=""/>
    <p class="primaryText">YOUR DREAM IS IN THE PRESENT</p>
    <p class="secondaryText">New BMW M8 Coupe Competition</p>
  </div>

  <div class="hero-container">

     <!-- left side -->
    <div class="left-side">
      <div class="tork">
        <p>Torque</p>
        <h1>370</h1>
      </div>
      <div class="zero-hundred">
        <p>0-100</p>
        <h1>3.2s</h1>
      </div>
    </div>

    <!-- middle side -->
    <div class="middle-side">
      <img src="bmw.png" alt="">
    </div>
    <!-- right side -->
    <div class="right-side">
      <div class="power">
        <p>Power</p>
        <h1>625</h1>
      </div>
      <div class="speed">
        <p>Speed</p>
        <h1>303</h1>
      </div>
    </div>
  </div>

</div>

<style>
    .hero-wrapper{
        flex-direction: row;
        justify-content: center;
        align-items: center;

    }
    .top-content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 0.5rem;

    }
    .top-content > img{
        width: 10rem;
    }
    .top-content > p{
        color: white;
    }
    
  .hero-container {
    display: grid;
    padding: 2rem;
   grid-template-columns: 1fr 2fr 1fr;
  }
  .left-side{
    display: flex;
    flex-direction: column;
    row-gap: 5rem;
    justify-content: center;
    align-items: center; 
   }
   .tork{
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    
   }
  .tork > p{
    color: rgba(128, 128, 128, 0.742);
  }
  .tork > h1{
    color: rgb(220, 219, 219);
    font-size: 1.5rem;
    text-align: center;
    font-weight:400;
  }
  .zero-hundred{
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
  }
  
  .zero-hundred > p {
    color: rgba(128, 128, 128, 0.742)
  }
  .zero-hundred > h1{
    color: rgb(220, 219, 219);
    font-size: 1.5rem;
    text-align: center;
    font-weight:400;
  }

   .right-side{
    display: flex;
    flex-direction: column;
    row-gap: 5rem;
    justify-content: center;
    align-items: center; 

   }

   .power {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
   }
   .power > p {
    color: rgba(128, 128, 128, 0.742);
    
   }
   .power > h1 {
    color: rgb(220, 219, 219);
    font-size: 1.5rem;
    text-align: center;
    font-weight:400;
   }
   .speed{
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
   }
   .speed > p {
    color: rgba(128, 128, 128, 0.742)
   }
.speed > h1{
  color: rgb(220, 219, 219);
    font-size: 1.5rem;
    text-align: center;
    font-weight:400;
}
   

  .middle-side > img{
    width: 100%;
  }
  .primaryText{
    font-size: 1.2rem;
    
  }
  .secondaryText{
    font-size: 0.8rem;
  }
</style>
