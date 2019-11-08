
<template>
 <div class = "bg">
  <div class="hero">
    <div>
      <h1 class="display-3">
        PROVO YSA<br>54th WARD BULLETIN</h1>
      <p class="lead">How to access the bulliten board: <br> 
      1. Click 'Login' at the top of the screen<br>
      2. Login with this information <br>
      username: mb935@byu.edu<br>
      password: CS260student<br>
      3. Click 'Bulletin Board' at the top of the screen
      </p>
    </div>
  </div>
  <div class="footer">
   <p><a href="https://github.com/mbisel/CP4.git"style="color:white;">GitHub</a></p>
</div>
  </div>
  
</template>

<style>

.bg {
  /* The image used */
  background-image: url("https://i.ibb.co/JkpgtnF/bulletin.jpg");

  /* Full height */
  height: 50%; 

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: repeat;
 
}
  .hero {
    height: 90vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    font-weight:900;
    
  }
  .hero .lead {
    font-weight: 500;
    font-size: 1.5rem;
    text-align:left;
    
  }
  .footer {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: #343A40;
   color: white;
   text-align: center;
}
</style>