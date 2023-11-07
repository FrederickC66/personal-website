<script setup>
</script>

<template>
  <main class="app">
      <nav class="header">
        <h1 class="logo">Frederick Cortez</h1>
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">Projects</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
  </main>
</template>

<style>
  .header, .nav-links, a {
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: black;
    border: 1px solid black;
    list-style-type: none;
    text-decoration: none;
    
  }

  .nav-links {
    
  }

  .nav-links li {
    text-decoration: none;
    color: black;
    padding: 0 50px;
  }

  
</style>