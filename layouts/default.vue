<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <nav class="navbar">
      <ul class="nav-list">
        <li class="nav-item"><a href="#home">Home</a></li>
        <li class="nav-item"><a href="#about">About</a></li>
        <li class="nav-item"><a href="#services">Services</a></li>
        <li class="nav-item"><a href="#portfolio">Portfolio</a></li>
        <li class="nav-item"><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <nuxt />
  </div>
</template>

<style>
.navbar {
  background-color: #333; /* Navbar background color */
  height: 60px; /* Navbar height */
}

.nav-list {
  display: flex; /* Display list items in a row */
  justify-content: center; /* Center align the list items */
  align-items: center; /* Vertically align the list items */
  height: 100%; /* Set list items height to 100% of navbar */
  list-style-type: none; /* Remove default list styles */
  margin: 0; /* Remove default margin */
  padding: 0; /* Remove default padding */
}

.nav-item {
  margin-right: 20px; /* Add spacing between list items */
}

.nav-item a {
  color: #fff; /* Link text color */
  text-decoration: none; /* Remove underline */
  transition: color 0.3s ease; /* Add smooth transition to link color */
}

.nav-item a:hover {
  color: #ff9800; /* Change link color on hover */
}

</style>
