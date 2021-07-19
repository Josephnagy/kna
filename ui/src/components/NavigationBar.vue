<template>
  <div>
      <b-navbar> 
        <b-navbar-brand> 
          <img src="https://kate-and-allys.com/wp-content/uploads/2016/08/kate_Alley-1small.png"> 
        </b-navbar-brand>
        <!-- Home -->
        <b-nav-item href="#">
          <router-link to="/">Home</router-link> 
        </b-nav-item>

        <!-- About -->
        <b-nav-item href="#">
          <router-link to="/about">About</router-link>
        </b-nav-item>

        <!-- Weddings -->
        <b-nav-item href="#">
          <router-link to="/">Weddings</router-link>
        </b-nav-item>

        <!-- Contact -->
        <b-nav-item href="#">
          <router-link to="/">Contact</router-link>
        </b-nav-item>

        <!-- Catering -->
        <b-nav-item href="#">
          <router-link to="/">Catering</router-link>
        </b-nav-item>

        <!-- Restaurant -->
        <b-nav-item href="#">
          <router-link to="/">Restaurant</router-link>
        </b-nav-item>

        <!-- Reviews -->
        <b-nav-item href="#">
          <router-link to="/">Reviews</router-link>
        </b-nav-item>

        <!-- Gift Cards -->
        <b-nav-item href="#">
          <router-link to="/">Gift Cards</router-link>
        </b-nav-item>

        <!-- Gallery -->
        <b-nav-item href="#">
          <router-link to="/">Gallery</router-link>
        </b-nav-item>

      </b-navbar>
    
  </div>
</template>

<script> 
export default {
  name: 'NavigationBar'
}
</script> 