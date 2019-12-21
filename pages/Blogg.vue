<template>
  <div>
    <div class="row">
      <div class="col">
        <b-button
          class="blogg-button"
          :class="visible ? null : 'collapsed'"
          :aria-expanded="visible ? 'true' : 'false'"
          aria-controls="collapse-4"
          @click="visible = !visible"
        >
          <h3>Hvordan velge riktig øl til skiva</h3>
        </b-button>
        <b-collapse id="collapse-4" v-model="visible" class="mt-2">
          <b-card class="bloggCard">
            <p>
              <img
              class="bloggImg"
                src="https://mymodernmet.com/wp/wp-content/uploads/2019/11/vinyl-records-2.jpg"
                alt
              />
              <br />
              <br />Å velge øl til musikken er ikke alltid en smal sak.
              <br />Bryggmesteren forklarer hvordan du velger riktig øl til skiva i denne artikkelen.
            </p>
            <a href="#" class="btn btn-outline-light mt-4 px-5">Les mer</a>

          </b-card>
        </b-collapse>
      </div>
    </div>
    <div class="row mt-4">
      <div class="col">
        <b-button class="blogg-button" v-b-toggle.collapse-1>
          <h3>Hvordan velge riktig humle</h3>
        </b-button>
        <b-collapse id="collapse-1" class="mt-2">
          <b-card class="bloggCard">
            <p>
              <img
              class="bloggImg"
                src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Hopfendolde-mit-hopfengarten.jpg"
                alt
              />
              <br />
              <br />Å velge riktig humle sort kan være litt vrient.
              <br />Her har vi laget en handy guide til hvordan du velger riktig humle til din egen ølbrygging.
            </p>
            <a href="#" class="btn btn-outline-light mt-4 px-5">Les mer</a>

          </b-card>
        </b-collapse>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      visible: true
    };
  }
};
</script>

<style>
.btn-secondary {
  display: block !important;
  width: 100%;
  background-color: #0d585c;
  color: #e3e3e3;
  border-radius: 0px;
}
.btn-secondary:focus {
  background-color: #00a8ac;
}
.btn-secondary:hover {
  background-color: #00a8ac;
}
.bloggCard {
  background-color: rgba(73, 73, 73, 0.23);
  border-radius: 0px;
}
.bloggImg{
  width: 100%;
}
</style>
