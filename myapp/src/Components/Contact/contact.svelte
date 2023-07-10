<script>
</script>

<div class="contact-wrapper">
  <div class="contact">
    <div class="address">
      <h3>BMW Montreal Centre</h3>
      <p>4090 Jean-Talon St.W. <br /> Montreal, QC H4P 1V5</p>
      <p>Tel. 844.855.4549</p>
    </div>

    <div class="address">
      <h3>BMW Montreal Centre</h3>
      <p>1633 Blvd. Armand <br /> Frappier</p>
      <p>Tel. 450.922.1633</p>
    </div>

    <div class="address">
      <h3>BMW Montreal Centre</h3>
      <p>8400 Boul. <br /> Taschrerau</p>
      <p>Tel. 450.922.1633</p>
    </div>

    <div class="address">
      <h3>Hamel BMW</h3>
      <p>620 Boulevard de la <br /> Seigneurie Quest,</p>
      <p>Tel. 450.987.8566</p>
    </div>

    <div class="location">
      <p>Choose Your Location</p>
      <button>Canada</button>
    </div>
  </div>
</div>

<footer>
  <div class="logos">
    <img src="bmw-logo.png" alt="" />
    <img src="bmw-performance.png" alt="" />
  </div>

  <div class="about">
    <p>About Us</p>
    <p>Terms&Conditions</p>
    <p>Contact Us</p>
  </div>

  <div class="social">
    <img src="twitter.png" alt="">
    <img src="instagram.png" alt="">
    <img src="youtube.png" alt="">
    <img src="facebook.png" alt="">
  </div>

</footer>

<style>
  .contact-wrapper {
    display: flex;
    padding: 3rem;
    justify-content: center;
    align-items: center;
  }
  .contact {
    display: flex;
    gap: 5rem;
  }
  .address {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  .address > h3 {
    color: white;
    font-weight: 400;
  }
  .address > p {
    color: #a7aeb1;
    font-size: 0.8rem;
  }

  .location {
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }
  .location > p {
    color: white;
    font-weight: 400;
  }
  .location > button {
    width: 100%;
    padding: 10px;
    background-color: #ffc80019;
    border-radius: 5px;
    color: white;
    border: 1px solid #ffc700;
    cursor: pointer;
  }

  footer {
    display:flex;
    justify-content: space-around;
    padding:0rem 5rem;
    
  }
  .logos {
    display: flex;
    justify-content: center;
    align-items: center;
   
    
  }
  .logos > img {
    width: 8rem;
  }

  .about{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 5rem;

  }
  .about >p{
    color: white;
    cursor: pointer;
  }
  .about >p:hover{
    color: #ffc700;
  }
  .social{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 2rem;
  }
 .social >img{
    width: 2rem;
    cursor: pointer;
 }
</style>
