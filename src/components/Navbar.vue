<template>
  <nav class="navbar bg-dark bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#" style="color: #f2f2f2">
        <img src="/src/assets/cipa.jpeg" alt="Logo" width="30" height="24" class="d-inline-block align-text-top">
        Syifa Web
      </a>
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <router-link id="home" class="nav-link" to="/">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link id="profile" class="nav-link" to="/profile">Profile</router-link>
        </li>
        <li class="nav-item">
          <router-link id="about" class="nav-link" to="/help">Travel</router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar"
};
</script>


