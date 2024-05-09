<template>
    <div id="home" class="pink-bg">
      <div class="container">
        <div class="content">
          <h1>Hey! I'm Kristine</h1>
          <div class="animated-picture"></div>
          <p> A curious and adventurous college
            <br>Studying computer science at Cordova Public College.
            <br> I find joy in learning and exploring.
          </p>
          <p class="name">College of Computer Studies</p> <!-- Add the name -->
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  #home {
    height: 100vh;
    width: 100vw; 
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden; 
  }
  
  .container {
    text-align: center;
  }
  
  .content {
    display: inline-block; 
    vertical-align: middle; 
    margin-right: 20px; 
  }
  
  .animated-picture {
    width: 390px;
    height: 400px;
    background-image: url('@/assets/kristine.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 50%;
    animation: stationary 4s linear infinite; 
  }
  
  @keyframes stationary {
    0% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(0deg); 
    }
  }
  
  
  .name {
    animation: eraseName 6s linear infinite; 
  }
  
  @keyframes eraseName {
    0% {
      opacity: 1;
    }
    100% {
      opacity: 0; /* Gradually reduce opacity to make the name disappear */
    }
  }
  
  
  .name {
    margin-top: 20px; /* Adjust the margin as needed */
  }
  
  /* Background image */
  .pink-bg {
    background-color: whitesmoke;
    /* background-image: url('@/assets/robertback.png');  */
    background-size: cover; 
    background-position: center; 
    margin: 0; 
    padding: 0; 
  }
  </style>
  
  