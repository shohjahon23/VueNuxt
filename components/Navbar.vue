<template>
  <nav class="navbar navbar-expand-lg bg-light">
    <a class="navbar-brand" href="#">Nuxt SSR</a>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            <nuxt-link exact no-prefetch active-class="active" class="nav-link" to="/">
              Home
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" class="nav-link" to="/about">
              About
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" class="nav-link" to="/users">
              Users
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" class="nav-link" to="/login">
              Login
            </nuxt-link>
          </li>
        </ul>
      </div>
  </nav>
</template>
