<template>
  <div >
      <div class="row mt-4">
      <div class="col">
        <h2> Velkommen til Marka Håndeverksbryggeri</h2>
          <h3 class="frontpageSubHeader">- Raffinert men rocka øl</h3>
      </div>
    </div>
    <div class="row frontpageRow">
      <div class="col-lg-6 frontpageImg">
        <img src="https://assets.newatlas.com/dims4/default/7a5cca9/2147483647/strip/true/crop/2000x1334+0+0/resize/1160x774!/quality/90/?url=https%3A%2F%2Fassets.newatlas.com%2Fb1%2F2e%2Fc3b2baab41a1b377d075b9001120%2Fdepositphotos-164150728-l-2015.jpg" class="img-fluid "  alt="">
      </div>
      <div class="col-lg-6 frontpageText
      text-center">
        <h2 class="text-center my-2">Velkommen!</h2>
        <p class="my-2">Vi er Marka Håndeverksbryggeri. Vi lager øl bassert på tradisjon men er ikke redd for å rocke det opp. Ølet vårt er i all hovedsak inspirert av Engelsk øl, men bryggmesteren er glad i å utforske nye typer og smaker. Ølet vårt er ukomplisert men mangler ikke på smak eller karakter.</p>
        <nuxt-link to="Produkter" class="btn btn-outline-light my-2"> Se Produkter</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
@media(max-width: 1249px) {
  .frontpageText{
    flex-basis: 100%;
    max-width: 100%;
  }
  .frontpageImg {
    flex-basis: 100%;
    max-width: 100%;
  }
}
.frontpageRow{
  margin-left: 15px;
  margin-right: 15px;

}
.frontpageImg{
  padding: 0px;
}
.frontpageText {
  padding: 0px;
  background-color: #1c1c1c;
}
.frontpageText p {
  padding: 20px;
  font-size: 25px;
}
.frontpageSubHeader{
  font-style: italic;
}
</style>


