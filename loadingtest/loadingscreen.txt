<template>
  <div class="col-12 container d-flex flex-column justify-content-center align-items-center p-0 m-0">
    <div class="p-0">
      <b-icon class="mr-4" id="circle" icon="circle-fill" font-scale="8"></b-icon>
      <b-icon class="mr-4" id="square" icon="square-fill" font-scale="8"></b-icon>
      <b-icon class="mr-4" id="triangle" icon="triangle-fill" font-scale="8"></b-icon>
    </div>
    <h1 class="mt-4">A carregar...</h1>
  </div>
</template>

<style>
.container {
  width: 100vw;
  height: 100vh;
  /* margin-left: auto;
  margin-right: auto;
  vertical-align: middle; */
  color: white;

  /* animaçao */
  animation: changeBackgroundColor 7s infinite;
}

#triangle {
  -webkit-animation: triangle 4s linear infinite;
  -moz-animation: triangle 4s linear infinite;
  -ms-animation: triangle 4s linear infinite;
  -o-animation: triangle 4s linear infinite;
  animation: triangle 4s linear infinite;

  
  animation-delay: 2s;
}
@keyframes triangle {
  0% {
    opacity: 5;
  }
  25% {
    opacity: 2.5;
  }
  50% {
    opacity: 0;
  }
  75% {
    opacity: 2.5;
  }
  100% {
    opacity: 5;
  }
}


#square {
  -webkit-animation: square 4s linear infinite;
  -moz-animation: square 4s linear infinite;
  -ms-animation: square 4s linear infinite;
  -o-animation: square 4s linear infinite;
  animation: square 4s linear infinite;

 
  animation-delay: 1s;
}
@keyframes square {
  0% {
    opacity: 5;
  }
  25% {
    opacity: 2.5;
  }
  50% {
    opacity: 0;
  }
  75% {
    opacity: 2.5;
  }
  100% {
    opacity: 5;
  }
}


#circle {
  -webkit-animation: circle 4s linear infinite;
  -moz-animation: circle 4s linear infinite;
  -ms-animation: circle 4s linear infinite;
  -o-animation: circle 4s linear infinite;  
  animation: circle 4s linear infinite;
}
@keyframes circle {
  0% {
    opacity: 5;
  }
  25% {
    opacity: 2.5;
  }
  50% {
    opacity: 0;
  }
  75% {
    opacity: 2.5;
  }
  100% {
    opacity: 5;
  }
}


@keyframes changeBackgroundColor {
  0% {
    background-color: #f54c25;
    opacity: 90%;
  }
  25% {
    background-color: #1995c9;
    opacity: 90%;
  }
  50% {
    background-color: #f7c901;
    opacity: 90%;
  }
  75% {
    background-color: #34b187;
    opacity: 90%;
  }
  100% {
    background-color: #f54c25;
    opacity: 90%;
  }
}
</style>