<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<Header />

<!-- <Nav /> -->

<main>
  <div class="subheading">
    <img src="/icons8-poison-100.png" alt="" />
    <h2>Yar Pirate Ipsum</h2>
    <img src="/icons8-poison-100.png" alt="" />
  </div>
  <div class="paragraph">
    <p>
      Maroon square-rigged rope's end spirits fathom tackle bilge rat careen
      cackle fruit splice the main brace. Arr to go on account bilge six
      pounders smartly yo-ho-ho yawl tack boatswain maroon. Barque hogshead
      coffer Buccaneer loot fire ship Shiver me timbers Blimey salmagundi reef.
    </p>

    <p>
      Draft scuttle rigging shrouds blow the man down belaying pin cog fluke
      strike colors killick. Gibbet case shot hulk main sheet landlubber or just
      lubber fathom Corsair coxswain reef Jolly Roger. Parrel jib man-of-war run
      a shot across the bow bounty maroon dead men tell no tales Cat o'nine
      tails ye swing the lead.
    </p>
  </div>
</main>

<style>
  h2 {
    font-family: "hyper-scrypt";
    color: #d9edff;
    font-size: 300%;
    transition: 3s;
  }

  .subheading {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-image: url("/HFC-Black-National-Flag.png");
    background-repeat: no-repeat;
    background-size: cover;
    padding: 2%;
  }

  p {
    font-family: basteleur;
    margin: 50px 250px;
    font-size: 20px;
    background-color: rgba(255, 255, 255, 0.5);
    transition: 0.5s;
  }

  .paragraph {
    background-image: url("/giphy.gif");
    padding: 80px 0px;
    background-repeat: no-repeat;
    background-position: left;
    transition: 7.5s;
  }

  main {
    background-image: url("/giphy (1).gif");
    background-position: bottom;
  }

  h2:hover {
    color: #880808;
    transition: 3s;
  }

  p:hover {
    background-color: whitesmoke;
    transition: 0.5s;
    transform: scale(1.1);
  }

  .paragraph:hover {
    background-position: right;
    transition: 7.5s;
  }
</style>
