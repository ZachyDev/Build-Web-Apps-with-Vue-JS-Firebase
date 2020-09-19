<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
    <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
      <li class="nav-item active">
        <router-link to="/" class="nav-link">Home</router-link>
      </li>
      <li class="nav-item">
          <router-link to="/about" class="nav-link">About</router-link>
      </li>
      <li class="nav-item">
          <router-link to="/services" class="nav-link">Services</router-link>
      </li>
    </ul>

  </div>
</nav>
</template>

<script>
export default {
    name: "Navbar",
    data() {
        return {

        }
    }
}
</script>

<style>

</style>