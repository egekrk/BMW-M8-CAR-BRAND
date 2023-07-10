<script>
</script>

<div class="equip-wrapper">
  <div class="left-side">
    <h1>APPERENCE</h1>
    <img src="steering-wheel.png" alt="" />
  </div>
  <div class="right-side">
    <h1>Equipments <br />& Highlights</h1>
    <p>
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis
      quam odio quas doloremque reprehenderit excepturi, aperiam unde, ea
      placeat tempora neque corrupti harum eligendi laborum nemo in? Facere fuga
      deleniti, ad ipsum voluptatum tenetur porro repellat earum pariatur nemo
      vel quos expedita sunt itaque recusandae commodi neque sint culpa! Sunt?
    </p>
    <button>Start Building</button>
  </div>
</div>

<style>
  .equip-wrapper {
    display: flex;
    padding: 0 10rem;
    justify-content: space-between;
    align-items: center;
    gap: 10rem;
  }

  .left-side {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  .left-side > h1 {
    font-weight: 400;
    color: white;
  }
  .left-side > img {
    width: 30rem;
  }

  .right-side {
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }
  .right-side > h1 {
    color: white;
    font-weight: 400;
  }
  .right-side > p {
    color: white;
    font-weight: 100;
    line-height: 2rem;
  }
  .right-side > button {
    width: 25%;
    border-radius: 5px;
    padding: 0.7rem;
    color: #ffc700;
    background-color: transparent;
    border: 1px solid #ffc700;
    cursor: pointer;
  }
</style>
