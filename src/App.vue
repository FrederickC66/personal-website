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
  <div class="hero">
    <div class="developer-name">
      <h1 class="title-name">Frederick Cortez</h1>
      <hr/>
      <p class="title-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </p>
      <button type="button">Projects</button>
      <button type="button">Contact</button>
    </div>
    <div class="about">
      <h2 class="about-title">About</h2>
      <hr/>
      <p class="about-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </p>
    </div>
  </div>
  <div class="projects">
    <h2>Projects</h2>
    <hr/>
    <div class="projects-card1">
      <img src="./assets/Dog 1.jpg" class="project-image"/>
      <h3>Project Title</h3>
      <hr/>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
    </div>
  </div>
  <div class="contact">
    <div>
      <h2>Contact</h2>
      <hr/>
      <label for="name">Name</label>
      <input type="text" id="name" placeholder="John Doe">
      <label for="message">Your Message</label>
      <input type="text" id="message" placeholder="Enter your message here">
      <label for="email">Email Address</label>
      <input type="text" id="email" placeholder="example@example.com">
      <button type="button">Submit</button>
    </div>
  </div>
</template>

<style>
  body {
    margin: 0 auto;
    margin-left: 0%;
    margin-right: 0%;
    margin-bottom: 0%;
    background-color: rgb(224, 215, 215);
    font-family: Arial;
  }

  .header, .nav-links, a {
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: black;
    list-style-type: none;
    text-decoration: none;
    margin-top: 0%;
  }

  .logo {
    padding: 0 5vw;
  }

  .nav-links li {
    color: black;
    padding: 0 5vw;
    
  }

  .developer-name {
    text-align: center;
    margin-top: 5%;
    margin-bottom: 10%;
    border: 1px solid black;
  }

  .about {
    text-align: center;
    border: 1px solid black;
  }

  hr {
    width:20%;
    margin:0 auto;
    align-items: center;
    margin-top: 0%;
    margin-bottom: 0%;
  }

  .project-image {
    max-width: 40%;
    height: auto;
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  .projects-card1 {
    display: grid;
    place-items: center;
    text-align: center;
  }
  
  .projects h1 {
    display: flex;
    text-align: center;
    margin-top: auto;
  }

  .contacts {
    display: grid;
    place-items: center;
    align-items: center;
    margin-top: 0%;
  }
</style>