<template>
  <div>
    <h1>Starter Vue Laravel with Router</h1>
    <p><strong>Current route path:</strong>{{ $route.fullPath }}</p>
    <nav>
        <div>
            <router-link class="link" to="/">Home</router-link> ||
            <router-link class="link" to="/about">About</router-link>
        </div>
    </nav>
    <main>
        <router-view />
    </main>
  </div>

</template>

<script setup>

</script>

