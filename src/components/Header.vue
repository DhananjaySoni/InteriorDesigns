
<template>
  <div class="header">
    <div class="header-bg">
      <b-jumbotron lead="Bootstrap v4 Components for Vue.js 2">
        <p>For more information visit website</p>
      </b-jumbotron>
    </div>
    <div>
      <b-navbar toggleable="md" type="dark" variant="info">
        

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="mx-auto">
            <b-nav-item href="#" class="mr-5"><router-link to="/">Home</router-link></b-nav-item>

            <b-nav-item href="#" class="mr-5"><router-link to="/about">About Us</router-link></b-nav-item>

            <b-nav-item href="#" class="mr-5">Contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>

  </div>
</template>


<script>
export default {};
</script>


<style scoped>
.header-bg {
  width: 100%;
}
.jumbotron {
  margin: 0;
}
</style>