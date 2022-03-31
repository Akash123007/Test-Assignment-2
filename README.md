# Test-Assignment-2


<template>
  <div>
  <div class="header-container">
    <div class="header">
      <ul>
        <li>Home</li>
        <li>About</li>
        <li>Contact Us</li>
      </ul>
    </div>
  </div>


  <!--Start Slideshow -->
  <div class="slideshow-container">

<!-- <div class="mySlides fade">
  <img src="./img/1.jpg" style="width:100%">
</div> -->

<div class="mySlides fade">
  <img src="./img/2.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <img src="./img/3.jpg" style="width:100%">
</div>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(-1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>
  <!--End Slideshow -->

<div>
  <div class=""></div>
</div>

  
  </div>
</template>
  
<script>
export default {
  name: "BootIndex",
  
};
</script>

<style scoped>
*{
  margin:0;
  padding: 0;
  box-sizing: border-box;
}
  .header li{
    background-color: black;
    color: white;
    display: inline-block;
    font-size: 20px;
    text-align: center;
    text-decoration: none;
    width: 500px;
    height: 50px;
    padding: 5px;
  }
/* slideshow */

.slideshow-container {
  position: relative;
  margin: auto;
}
  .prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

.prev {
  left: 0;
  border-radius: 3px 0 0 3px;
}


.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

</style>
