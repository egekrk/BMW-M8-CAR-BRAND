<script>
  
  import Carousel from "../Components/Carousel/carousel.svelte";
  import Contact from "../Components/Contact/contact.svelte";
  import Engine from "../Components/Engine/engine.svelte";
  import Equipments from "../Components/Equipments/equipments.svelte";
  import Header from "../Components/Header/header.svelte";
  import Hero from "../Components/Hero/hero.svelte";
  import Keys from "../Components/Keys/keys.svelte";
</script>

<Header />
<Hero />
<Equipments />
<Keys />
<Engine />
<Carousel />
<Contact/>

<main>
  <slot />
</main>

<style>
  :global(body, *) {
    margin: 0;
    padding: 0;
    font-family: "Montserrat", sans-serif;
    background: #151f21;
  }
</style>
