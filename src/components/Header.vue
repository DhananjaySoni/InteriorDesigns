
<template>
  <div class="header">
    <div class="header-bg">
      <b-jumbotron>
      </b-jumbotron>
    </div>
    <div>
      <b-navbar toggleable="md" type="dark">
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav fixed>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="mx-auto">
            <b-nav-item href="#" class="mr-5">
              <router-link to="/">Home</router-link>
            </b-nav-item>
            <b-nav-item href="#" class="mr-5">
              <router-link to="/about">About Us</router-link>
            </b-nav-item>
            <b-nav-item href="#" class="mr-5">Contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>


<style scoped>
.navbar {
  background: #3b1f16;
}
.header-bg {
  width: 100%;
}
.jumbotron {
  height:210px;
  margin: 0;
  background:url(/logo.png) no-repeat center; 
  background-size:cover;
}
</style>