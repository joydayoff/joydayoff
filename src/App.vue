<template>
  <div class="site-shell">
    <header class="hero">
      <nav class="top-nav">
        <div class="brand">Vue Free Website</div>
        <div class="nav-links">
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">Services</RouterLink>
          <RouterLink to="/contact">Contact</RouterLink>
        </div>
      </nav>

      <section class="hero-copy">
        <p class="eyebrow">Vue CLI + GitHub Pages</p>
        <h1>Launch a clean multi-page-feel Vue site for free.</h1>
        <p class="lede">
          This starter gives you a simple structure for a personal brand site,
          portfolio, or service landing page with fast deployment and custom
          domain support.
        </p>
      </section>
    </header>

    <main class="content">
      <RouterView />
    </main>
  </div>
</template>

<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>
