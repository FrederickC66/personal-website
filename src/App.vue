<script setup>
</script>

<template>
  <div class="navbar">
    <nav class="header">
      <h2 class="logo">fcportfolio.app</h2>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </div>
  <div class="title-page">
    <div class="hero">
      <h1 class="title-name">Frederick Cortez</h1>
      <hr/>
      <p class="title-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </p>
    </div>
    <div class="about">
      <h2 class="about-title">About</h2>
      <hr/>
      <p class="about-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </p>
    </div>
  </div>
</template>

<style>
  body {
    margin: 0 auto;
  }

  .header, .nav-links, a {
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: black;
    list-style-type: none;
    text-decoration: none;
  }

  .logo {
    padding: 0 5vw;
  }

  .nav-links li {
    color: black;
    padding: 0 5vw;
  }

  .hero {
    text-align: center;
    margin-top: 5%;
    margin-bottom: 10%;
  }

  .about {
    text-align: center;
  }

  hr {
    width:20%;
    margin:0 auto;
  }

</style>