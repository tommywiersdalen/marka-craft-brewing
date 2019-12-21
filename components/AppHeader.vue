<template>
  <div >
    <div class="row">
      <div class="col">
        <div class="headerTextWrapper">
          <h1 class="text-center">Marka</h1>
          <h2 class="text-center">HåndverksBryggeri</h2>
        </div>
        <div class="headImgBox text-center">
          <img
            src="http://clipart-library.com/images_k/bomber-plane-silhouette/bomber-plane-silhouette-6.png"
            class="headerImg"
            alt
          />
        </div>
      </div>
    </div>
    <div class="nav-wrapper mt-2">
      <b-navbar toggleable="lg" type="dark">
        <b-navbar-brand class="navbrand"><nuxt-link to="/"> Marka HåndverksBryggeri</nuxt-link></b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item>
              <nuxt-link to="/">Hjem</nuxt-link>
            </b-nav-item>
            <b-nav-item>
              <nuxt-link to="OmOss">Om oss</nuxt-link>
            </b-nav-item>
            <b-nav-item>
              <nuxt-link to="Produkter">Produkter</nuxt-link>
            </b-nav-item>
            <b-nav-item>
              <nuxt-link to="Bryggeriet">Bryggeriet</nuxt-link>
            </b-nav-item>
              <b-nav-item ><nuxt-link to="Blogg">Blogg</nuxt-link></b-nav-item>
              <b-nav-item ><nuxt-link to="blog/_blog">Blog</nuxt-link></b-nav-item>
          </b-navbar-nav>

        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppHeader"
};
</script>

<style>
.nav-wrapper{
  border-top: 2px solid rgb(44, 44, 44);
  background-color: black
}
.headerTextWrapper {
 font-family: Inria;
 position: relative;
 top: 60px;
}
.headerImg {
  width: 200px;
  border: 2px solid rgb(44, 44, 44);
  border-radius: 100%;
  margin-top: -92px;
}
.navbrand{
  font-family: Inria;
  color: #e3e3e3;
}
</style>
