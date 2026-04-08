<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-dark unique-color">
      
      <!-- Toggle button -->
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Navbar content -->
      <div class="collapse navbar-collapse" id="navbarSupportedContent">

        <ul class="navbar-nav mx-auto align-items-center">

          <!-- Home -->
          <li class="nav-item">
            <a class="nav-link">Home</a>
          </li>

          <!-- Committees -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" data-toggle="dropdown">
              Committees
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item">Advisory Committee</a>
              <a class="dropdown-item">Organising Committee</a>
              <a class="dropdown-item">Technical Committee</a>
            </div>
          </li>

          <!-- Call for Papers -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" data-toggle="dropdown">
              Call for Papers
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item">Call for Papers</a>
              <a class="dropdown-item">Tracks / Topics</a>
              <a class="dropdown-item">Special Session</a>
              <a class="dropdown-item">Camera Ready Submission Instructions</a>
            </div>
          </li>

          <!-- Normal links -->
          <li class="nav-item"><a class="nav-link">Keynote Speakers</a></li>
          <li class="nav-item"><a class="nav-link">Program Schedule</a></li>
          <li class="nav-item"><a class="nav-link">Workshops</a></li>
          <li class="nav-item"><a class="nav-link">Registration</a></li>

          <!-- Plan Travel -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" data-toggle="dropdown">
              Plan Travel
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item">About India</a>
              <a class="dropdown-item">About Raipur</a>
              <a class="dropdown-item">Travelling to Raipur</a>
              <a class="dropdown-item">Conference Venue</a>
              <a class="dropdown-item">Accommodation</a>
            </div>
          </li>

          <li class="nav-item"><a class="nav-link">Downloads</a></li>
          <li class="nav-item"><a class="nav-link">Partners</a></li>

          <li class="nav-item">
            <router-link class="nav-link" to="/tourist">
              Tourists Attraction
            </router-link>
          </li>

          <li class="nav-item"><a class="nav-link">Contact Us</a></li>

        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
/* 🔥 Center everything */
.navbar-nav {
  gap: 10px;
}

/* Equal spacing */
.nav-item {
  display: flex;
  align-items: center;
}

/* Clean hover */
.nav-link {
  cursor: pointer;
  padding: 8px 12px;
}

/* Dropdown fix */
.dropdown-menu {
  text-align: left;
}
</style>