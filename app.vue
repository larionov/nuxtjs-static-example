<template>
  <div>
    <ul>
      <li><NuxtLink to="/">Home page</NuxtLink></li>
      <li><NuxtLink to="/one">Page one</NuxtLink></li>
      <li><NuxtLink to="/two">Page two</NuxtLink></li>
    </ul>
    <!-- Markup shared across all pages, ex: NavBar -->

    <NuxtPage />
  </div>
</template>
