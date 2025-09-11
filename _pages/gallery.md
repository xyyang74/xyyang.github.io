---
permalink: /gallery/
layout: single
author_profile: false
---
# 🌿 Wellcome to my nature photo gallery
<div class="carousel">
  <div class="slides">
    <img src="/images/gallery/photo1.jpg" alt="Photo 1">
    <img src="/images/gallery/photo2.jpg" alt="Photo 2">
    <img src="/images/gallery/photo3.jpg" alt="Photo 3">
    <img src="/images/gallery/photo4.jpg" alt="Photo 4">
    <img src="/images/gallery/photo5.jpg" alt="Photo 5">
    <img src="/images/gallery/photo6.jpg" alt="Photo 6">
  </div>
  <button class="prev" onclick="plusSlides(-1)">❮</button>
  <button class="next" onclick="plusSlides(1)">❯</button>
</div>

<script>
let slideIndex = 0;
const slides = document.querySelectorAll(".carousel .slides img");
showSlide(slideIndex);

function plusSlides(n) {
  slideIndex = (slideIndex + n + slides.length) % slides.length;
  showSlide(slideIndex);
}

function showSlide(n) {
  slides.forEach((img, i) => {
    img.style.display = (i === n) ? "block" : "none";
  });
}
</script>

<style>
.carousel {
  position: relative;
  max-width: 1200px;
  margin: auto;
}
.carousel .slides img {
  height: 600px;
  display: block;      /* 让它能被居中 */
  margin: auto;        /* 居中对齐 */
  display: none;
}
.carousel .prev, .carousel .next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.4);
  color: white;
  border: none;
  padding: 0.5em 1em;
  cursor: pointer;
}
.carousel .prev { left: 0; }
.carousel .next { right: 0; }
</style>

---

[⬅ Back to my academic page](/)