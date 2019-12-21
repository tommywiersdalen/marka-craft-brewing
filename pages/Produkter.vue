<template>
  <div>
    <div class="row">
      <div class="col">
        <h3>Øl Polstyrke</h3>
      </div>
    </div>
    <div class="row mt-4">
      <div class="col-lg-4 mb-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <h4 class="productTitle">Lurven</h4>
          </div>
          <div class="flip-card-back">
            <h3 class="productBackTitle mt-4 mb-2">Lurven</h3>
            <p class="productBackText mt-2 mb-4 p-4">
              Lurven er en leken IPA. Ver varsom denne pusen har klør.
              <br />Fruktige og søte toner av citrus og røde bær,
              <br />blir fulgt av en skarp og forfriskende ettersmak.
            </p>
            <nuxt-link to="lurven" class="btn btn-outline-light mt-4 px-5"> Se Produkt</nuxt-link>
          </div>
        </div>
      </div>
      <div class="col-lg-4 mb-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <h4 class="productTitle">Godokk</h4>
          </div>
          <div class="flip-card-back">
            <h3 class="productBackTitle mt-4 mb-2">Godokk</h3>
            <p class="productBackText mt-2 mb-4 p-4">
              Godokk er en tradsjonell Engelsk ale for deg som vil gå tur i skogen.
              <br />Fyldig maltsmak med akkuratt passe bitter med hint av granskudd.
            </p>
            <a href="#" class="btn btn-outline-light mt-4 px-5">Se Produkt</a>
          </div>
        </div>
      </div>
      <div class="col-lg-4 mb-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <h4 class="text-white productTitle">De Underjordiske</h4>
          </div>
          <div class="flip-card-back">
            <h3 class="productBackTitle mt-4 mb-2">De Underjordiske</h3>
            <p class="productBackText mt-2 mb-4 p-4">
              Pass på her er det mørke krefter på gang!
              <br />De Underjordiske er en kraftig stout,
              <br />Med smak av kaffe, sjokolade og krem.
              <br />skremmende godt!
            </p>
            <nuxt-link to="DeUnderjordiske" class="btn btn-outline-light mt-4 px-5">Se Produkt</nuxt-link>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <h3>Øl Butikkstyrke</h3>
      </div>
    </div>
    <div class="row mt-4">
      <div class="col-lg-4 mb-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <h4 class=" productTitle">Bærtyver!</h4>
          </div>
          <div class="flip-card-back">
            <h3 class="productBackTitle mt-4 mb-2">Bærtyver!</h3>
            <p class="productBackText mt-2 mb-4 p-4">
              Bærtyver er en Belgisk frukt øl med en noe uvanlig karakter.
              <br />Denne har nemlig nemlig blitt tilsatt selvdyrkede rips.
              <br />Foriskende syrlig uten at den blir for skarp.
            </p>
            <a href="#" class="btn btn-outline-light mt-4 px-5">Se Produkt</a>
          </div>
        </div>
      </div>
      <div class="col-lg-4 mb-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <h4 class=" productTitle">Salbøtt</h4>
          </div>
          <div class="flip-card-back">
            <h3 class="productBackTitle mt-4 mb-2">Salbøtt</h3>
            <p class="productBackText mt-2 mb-4 p-4">
              Salbøtt er en lys og lett pils som passer til varme sommerdager.
              <br />Lett maltsødme og mild bitterhet, men med et snev av citrus og nyklippet gress.
            </p>
            <a href="#" class="btn btn-outline-light mt-4 px-5">Se Produkt</a>
          </div>
        </div>
      </div>
      <div class="col-lg-4 mb-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <h4 class=" productTitle">Heståsen</h4>
          </div>
          <div class="flip-card-back">
            <h3 class="productBackTitle mt-4 mb-2">Heståsen</h3>
            <p class="productBackText mt-2 mb-4 p-4">
              Heståsen er en porter som passer for de som liker å vandre.
              <br />Smak av brød og kaffe med en rund profil.
            </p>
            <a href="#" class="btn btn-outline-light mt-4 px-5">Se Produkt</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.productTitle {
  position: relative;
  top: 50%;
  background-color: #1c1c1c;
  padding-top: 20px;
  padding-bottom: 20px;;
  backface-visibility: hidden;
}
.productImg {
  max-width: 100%;
  width: 100%;
  min-height: 100%;
  height: 100%;
}
/* The flip card container - set the width and height to whatever you want. We have added the border property to demonstrate that the flip itself goes out of the box on hover (remove perspective if you don't want the 3D effect */
.flip-card {
  background-color: transparent;
  max-width: 100%;
  width: 100%;
  height: 380px;
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
}

/* This container is needed to position the front and back side */
.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

/* Do an horizontal flip when you move the mouse over the flip box container */
.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

/* Position the front and back side */
.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
}

/* Style the front side (fallback if image is missing) */
.flip-card-front {
  background-color: rgba(73, 73, 73, 0.23);
  background-image: url("https://www.searchpng.com/wp-content/uploads/2018/12/Beer-Bottle-Png-715x715.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: 380px;
}

/* Style the back side */
.flip-card-back {
  background-color: #1c1c1c;
  transform: rotateY(180deg);
}
</style>
