<template>
  <nav
    class="navbar fixed-top navbar-expand-sm navbar-light bg-body-tertiary"
    data-bs-theme="dark"
  >
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Organic Roasters</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a href="#home" class="nav-link">Home</a>
          </li>
          <li class="nav-item">
            <a href="#about" class="nav-link">About Us</a>
          </li>
          <li class="nav-item">
            <a href="#order" class="nav-link">Order</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isCollapsed: true,
    };
  },
  methods: {
    toggleNavbar() {
      this.isCollapsed = !this.isCollapsed;
    },
  },
};
</script>
