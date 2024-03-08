<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<head>
  <style>
    @import url("https://fonts.googleapis.com/css2?family=Comfortaa:wght@300..700&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Delius+Swash+Caps&family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&family=Rowdies:wght@300;400;700&display=swap");
  </style>
</head>

<Header />

<!-- <Nav /> -->

<main>
  <div class="h2">
    <h2>cupcake ipsum ❤︎</h2>
  </div>

  <div class="text">
    <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
    </p>

    <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan
      pastry. Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o
      fruitcake chocolate bar chupa chups chocolate sesame snaps candy. Sweet
      roll carrot cake cake jelly candy jujubes gummi bears jelly-o. Oat cake
      wafer chocolate bar sweet roll macaroon soufflé powder sugar plum tart.
    </p>
  </div>
  <img src="cupcakes.jpg" alt="" />
</main>

<style>
  main {
    background-color: #fcd9df;
    display: grid;
    grid:
      "h    i" auto
      "p    i" auto
      "p    i" auto
      / 3fr 3fr;
  }
  h2 {
    grid-area: h;
    font-family: "Delius Swash Caps", cursive;
    font-weight: 400;
    font-style: normal;
    color: #ea4b63;
    font-size: 4em;
    margin: 5% 7% 2%;
    width: 50%;
  }

  .text p {
    font-family: "Comfortaa", sans-serif;
    font-weight: 400;
    font-style: normal;
    color: #ea4b63;
    font-size: 1.5em;
    margin: 7%;
  }

  img {
    grid-area: i;
    height: 800px;
    margin-right: 0px;
  }
</style>
