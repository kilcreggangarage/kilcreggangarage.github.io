---
theme: default
---

---

<meta name="viewport" content="width=device-width, initial-scale=1">


{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  <img src="/kilcreggangarage.github.io{{ myimage.path }}?raw=true">
{% endfor %}

<!--
<div class="w3-content w3-display-container">
  <img class="mySlides" src="assets/images/1920x540-1.jpg?raw=true" style="width:100%">
  <img class="mySlides" src="assets/images/1920x540-3.jpg?raw=true" style="width:100%">
  <img class="mySlides" src="assets/images/670x510.png?raw=true" style="width:100%">

  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>
-->

---
