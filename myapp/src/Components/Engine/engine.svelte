<script>
</script>

<div class="engine-wrapper">
  <div class="left-side">
    <h1>ENGINE</h1>
    <p>
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis
      quam odio quas doloremque reprehenderit excepturi, aperiam unde, ea
      placeat tempora neque corrupti harum eligendi laborum nemo in? Facere fuga
      deleniti, ad ipsum voluptatum tenetur porro repellat earum pariatur nemo
      vel quos expedita sunt itaque recusandae commodi neque sint culpa! Sunt?
    </p>
    <button>Start Building</button>
  </div>
  <div class="right-side">
    <h1>PERFORMANCE</h1>
    <img src="engine.png" alt="" />
  </div>
</div>

<style>
  .engine-wrapper {
    display: flex;
    padding: 5rem 10rem;
    justify-content: space-between;
    align-items: center;
    gap: 10rem;
  }

  .left-side{
    display: flex;
    flex-direction: column;
    gap: 3rem;
  }
  .left-side>h1{
    color: white;
    font-weight: 400;
  }
  .left-side>p{
    color: white;
    font-weight: 100;
    line-height: 2rem;
  }
  .left-side>button{
    width: 25%;
    border-radius: 5px;
    padding: 0.7rem;
    color:#ffc700;
    background-color: transparent;
    border: 1px solid #ffc700;
    cursor: pointer;
  }

  .right-side{
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  .right-side>h1{
    color: white;
    font-weight: 400;
  }
  .right-side>img{
    width: 30rem;
  }
</style>
