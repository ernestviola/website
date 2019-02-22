<template>
  <!-- Navigation -->
  <nav class="vsd-header navbar navbar-expand-lg navbar-light fixed-top py-3">
    <div class="container">
      <a class="navbar-brand js-scroll-trigger" href="#page-top">{{ title }}</a>
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ml-auto my-2 my-lg-0">
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#about">About</a>
            <!-- <router-link to="" >About</router-link> -->
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  props: ['title']
}
</script>


<style>
.vsd-header {
  background: grey;
}
</style>
