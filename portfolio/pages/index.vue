<template>
  <section class="section">
  <video autoplay muted loop id="videomi">
  <source src="../assets/atomic.mp4" type="video/mp4"/>
  </video>

  <div class= "container ">
   
  
<header class="viewport-header">
  <h1>
    I'm a fullstack Developer
    <span>B4 consults</span>
  </h1>
</header>

  </div>
  </section>
</template>
<style scoped>
.section{
  background-color: black;
}
#videomi{
  position: fixed;
  object-fit: cover;
  top: 0.1;
  left: 0;
  width: 100vw;
  height: 100vh;
}
.container{
   position: relative;
  height: 100vh;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
}
.viewport-header{
position: relative;
  height: 50vh;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
}
  h1 {font-family: 'Syncopate', sans-serif;
  color: white;
  
  text-transform: uppercase;
  letter-spacing: 3vw;
  line-height: 1.2;
  font-size: 3vw;
  text-align: center;
 
}
 span{
     display: block;
    font-size: 10vw;
    letter-spacing: -1.3vw;
  }

</style>