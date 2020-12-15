<template>
  <header>
    <b-navbar fixed="top"  toggleable="lg" variant="light">
      <b-navbar-brand href="#">
        <img width="100%" src="../assets/img/BOOStudio_Logo.png" alt="">
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item link-classes="header-link" href="#">Home</b-nav-item>
          <b-nav-item link-classes="header-link" href="#">About Us</b-nav-item>
          <b-nav-item link-classes="header-link" href="#">What Do We Do</b-nav-item>
          <b-nav-item link-classes="header-link" href="#">
            <b-icon icon="telephone-fill"></b-icon>
          </b-nav-item>
          <b-nav-item link-classes="header-link" href="#">
            <b-icon icon="envelope-fill"></b-icon>
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </header>
</template>

<script>
  export default {
    name: "Header"
  }
</script>

<style scoped>
  .header-link {
    color: #cf551c !important;
    font-size: 16px;
    font-weight: bold;
  }
</style>
