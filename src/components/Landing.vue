<template>
<div class="jumbotron">
  <b-jumbotron>
    <div class="socials">
      <a href="https://www.facebook.com/podmarketinginc/">
        <img id="facebook" class="fb hvr-grow-shadow" src="https://puu.sh/HQJtb/1d85c2c113.png" />
      </a>
      <a href="https://www.podmarketinginc.com/">
        <img id="googleplus" class="fb hvr-grow-shadow" src="https://puu.sh/HQJyp/41b1a644c6.png" />
      </a>
      <a href="https://twitter.com/podmarketinginc?lang=en">
        <img id="twitter" class="fb hvr-grow-shadow" src="https://puu.sh/HQJyy/36692d3607.png" />
      </a>
      
    </div>


    <div class="title">
      <b-img src="https://puu.sh/HQJpJ/81b40c44bc.png" fluid />
    </div>
    
    <div class="scroll">
      <b-img src="https://puu.sh/HQJrB/4397b47f16.png" />
    </div>
    


  </b-jumbotron>
</div>

    
</template>

<script>
export default {
  name: 'Landing',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.jumbotron {
  background-image: url("https://puu.sh/HQJm2/232fc8e666.jpg");
  background-size: cover;
  height: 100vh;
}
.scroll {
  padding-top: 5rem;
}

.fb {
  padding-right: 2rem;
  filter: brightness(0) invert(1);
}

.hvr-grow-shadow {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: perspective(1px) translateZ(0);
  transform: perspective(1px) translateZ(0);
  box-shadow: 0 0 5px rgba(0, 0, 0, 0);
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  -webkit-transition-property: box-shadow, transform;
  transition-property: box-shadow, transform;
}

.hvr-grow-shadow:hover, .hvr-grow-shadow:focus, .hvr-grow-shadow:active {
  box-shadow: 0 10px 10px -10px rgba(0, 0, 0, 0.5);
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
}

.socials {
  padding-right: 60rem;
  padding-top: 2rem;
  padding-bottom: 3rem;
}
</style>
