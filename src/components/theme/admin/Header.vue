<template>
  <header class="topbar">
    <nav class="navbar top-navbar navbar-expand-md navbar-light">
      <!-- ============================================================== -->
      <!-- Logo -->
      <!-- ============================================================== -->
      <div class="navbar-header">
        <NuxtLink :to="{ name: 'admin' }" class="navbar-brand">
          <!-- Logo icon --><b>
            <img src="/admin/images/logo-icon.png" alt="homepage" class="dark-logo" />
          </b>
          <!--End Logo icon -->
          <!-- Logo text -->
          <span>
            <img src="/admin/images/logo-text.png" alt="homepage" class="dark-logo" />
          </span>
        </NuxtLink>
      </div>
      <!-- ============================================================== -->
      <!-- End Logo -->
      <!-- ============================================================== -->
      <div class="navbar-collapse">
        <!-- ============================================================== -->
        <!-- toggle and nav items -->
        <!-- ============================================================== -->
        <ul class="navbar-nav me-auto">
          <!-- This is  -->
          <li class="nav-item"> <a class="nav-link nav-toggler hidden-md-up waves-effect waves-dark"
              href="javascript:void(0)"><i class="ti-menu"></i></a> </li>
        </ul>
        <!-- ============================================================== -->
        <!-- User profile and search -->
        <!-- ============================================================== -->
        <ul class="navbar-nav my-lg-0">
          <!-- ============================================================== -->
          <!-- Search -->
          <!-- ============================================================== -->
          <li class="nav-item hidden-xs-down search-box"> <a class="nav-link hidden-sm-down waves-effect waves-dark"
              href="javascript:void(0)"><i class="ti-search"></i></a>
            <form class="app-search">
              <input type="text" class="form-control" placeholder="Search & enter"> <a class="srh-btn"><i
                  class="ti-close"></i></a>
            </form>
          </li>
          <!-- ============================================================== -->
          <!-- Profile -->
          <!-- ============================================================== -->
          <li class="nav-item">
            <a class="nav-link waves-effect waves-dark" href="#"><img src="/admin/images/users/1.jpg" alt="user"
                class="profile-pic" /></a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script setup>
</script>