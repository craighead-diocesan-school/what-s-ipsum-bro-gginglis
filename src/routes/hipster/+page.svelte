<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<head>
  <style>
    @import url("https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Rowdies:wght@300;400;700&display=swap");
    @import url("https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&family=Rowdies:wght@300;400;700&display=swap");
  </style>
</head>

<Header />

<!-- <Nav /> -->

<main>
  <div class="subheading">
    <h2>Hipster Ipsum</h2>
    <img src="/icons8-mustache-100.png" alt="" />
  </div>

  <div class="p1">
    <p>
      Fingerstache tofu pickled vibecession kitsch lyft blackbird spyplane vegan
      craft beer keytar banh mi thundercats. Hashtag heirloom vape scenester
      paleo hexagon. Blackbird spyplane pok pok DIY heirloom scenester food
      truck kale chips pabst, bitters raw denim artisan waistcoat seitan
      freegan.
    </p>
  </div>

  <div class="line"></div>

  <div class="p2">
    <p>
      Put a bird on it vibecession fashion axe YOLO asymmetrical. VHS photo
      booth listicle fam truffaut subway tile yr cred chicharrones semiotics
      biodiesel green juice microdosing whatever. Truffaut praxis PBR and B
      tattooed street art. Prism jean shorts pickled vegan. Vegan praxis cronut
      kitsch pop-up. Letterpress street art mlkshk marxism.
    </p>
  </div>
</main>

<style>
  main {
    background-color: #bfcdff;
    display: grid;
    grid:
      "h    h     h" 50vh
      "p1    l    ." auto
      ".     l    p2" auto
      / 3fr 2px 3fr;
  }
  .subheading {
    color: #446dff;
    grid-area: h;
    text-align: center;
    justify-content: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 200%;
    font-family: "Rowdies", sans-serif;
  }
  .p1 {
    color: #446dff;
    grid-area: p1;
    font-family: "Lato", sans-serif;
    font-weight: 400;
    font-style: normal;
    font-size: 150%;
    margin: 2% 10%;
    text-align: justify;
  }

  .line {
    grid-area: l;
    background-color: #446dff;
    height: 100%;
  }
  .p2 {
    color: #446dff;
    grid-area: p2;
    font-family: "Lato", sans-serif;
    font-weight: 400;
    font-style: normal;
    font-size: 150%;
    margin: 2% 10%;
    text-align: justify;
  }

  img {
    height: 150px;
    width: 150px;
  }
</style>
