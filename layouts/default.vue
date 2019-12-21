<template>
  <div class="container fill">
    <AppHeader class="header mb-4" />
    <div class="content">
      <nuxt />
    </div>
    <AppFooter class="footer mt-4" />
  </div>
</template>
<script>
import AppHeader from "../components/AppHeader";
import AppFooter from "../components/AppFooter";
export default {
  components: {
    AppHeader,
    AppFooter
  }
};
</script>
<style>
body {
  height: 100vh;
  min-height: 100vh;
  /* background-color: #058487; */
  background: linear-gradient(
    90deg,
    rgba(52, 68, 70, 1) 0%,
    rgba(13, 88, 92, 1) 39%,
    rgba(0, 168, 172, 1) 100%
  );
 /*  background-image: url("http://clipart-library.com/images_k/bomber-plane-silhouette/bomber-plane-silhouette-6.png");
  background-attachment: fixed; */
  font-family: 'Roboto Slab', serif;
  color: #e3e3e3;

}
#__nuxt {
  height: 100%;
  min-height: 100%;
}
#__layout {
  height: 100%;
  min-height: 100%;
}
.fill {
  height: 100%;
  min-height: 100%;
  position: relative;
  max-width: 100%;
  padding: 0;
}
.header {
  background-color: #1c1c1c;
}
.footer {
  height: 10vh;
  background-color: #1c1c1c;
  width: 100%;
  max-width: 100%;
  display: grid;
  flex-wrap: wrap;
  align-items: center;
}
.content {
  min-height: calc(100vh - 70px);
}
.row {
  margin: 0;
}
.btn-outline-light {
  color: #fff;
  background-color: #0d585c;
  border-color: white;
}
.btn-outline-light:hover,
.btn-primary:focus,
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #00a8ac;
  border-color: white;
}

.navbar-dark .navbar-nav .nav-link:hover {
  color: #0d585c;
}
a{
  color:#e3e3e3;
  text-decoration: none;
}
a:hover{
  color:#0d585c;
  text-decoration: none;
}
</style>
