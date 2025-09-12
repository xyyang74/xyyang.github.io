---
permalink: /gallery/
layout: single
author_profile: false
title: " "
---
# 🌿 Wellcome to my nature photo gallery
<div class="carousel">
  <div class="slides">
    <img src="/images/gallery/photo1.webp" alt="Photo 1">
    <img src="/images/gallery/photo2.webp" alt="Photo 2">
    <img src="/images/gallery/photo3.webp" alt="Photo 3">
    <img src="/images/gallery/photo4.webp" alt="Photo 4">
    <img src="/images/gallery/photo5.webp" alt="Photo 5">
    <img src="/images/gallery/photo6.webp" alt="Photo 6">
    <img src="/images/gallery/photo7.webp" alt="Photo 7">
    <img src="/images/gallery/photo8.webp" alt="Photo 8">
    <img src="/images/gallery/photo9.webp" alt="Photo 9">
    <img src="/images/gallery/photo10.webp" alt="Photo 10">
    <img src="/images/gallery/photo11.webp" alt="Photo 11">
    <img src="/images/gallery/photo12.webp" alt="Photo 12">
    <img src="/images/gallery/photo13.webp" alt="Photo 13">
    <img src="/images/gallery/photo14.webp" alt="Photo 14">
    <img src="/images/gallery/photo15.webp" alt="Photo 15">
    <img src="/images/gallery/photo16.webp" alt="Photo 16">
    <img src="/images/gallery/photo17.webp" alt="Photo 17">
    <img src="/images/gallery/photo18.webp" alt="Photo 18">
    <img src="/images/gallery/photo19.webp" alt="Photo 19">
    <img src="/images/gallery/photo20.webp" alt="Photo 20">
    <img src="/images/gallery/photo21.webp" alt="Photo 21">
    <img src="/images/gallery/photo22.webp" alt="Photo 22">
    <img src="/images/gallery/photo23.webp" alt="Photo 23">
    <img src="/images/gallery/photo24.webp" alt="Photo 24">
    <img src="/images/gallery/photo25.webp" alt="Photo 25">
    <img src="/images/gallery/photo26.webp" alt="Photo 26">
    <img src="/images/gallery/photo27.webp" alt="Photo 27">
    <img src="/images/gallery/photo28.webp" alt="Photo 28">
    <img src="/images/gallery/photo29.webp" alt="Photo 29">
    <img src="/images/gallery/photo30.webp" alt="Photo 30">
    <img src="/images/gallery/photo31.webp" alt="Photo 31">
    <img src="/images/gallery/photo32.webp" alt="Photo 32">
    <img src="/images/gallery/photo33.webp" alt="Photo 33">
    <img src="/images/gallery/photo34.webp" alt="Photo 34">
    <img src="/images/gallery/photo35.webp" alt="Photo 35">
    <img src="/images/gallery/photo36.webp" alt="Photo 36">
    <img src="/images/gallery/photo37.webp" alt="Photo 37">
    <img src="/images/gallery/photo38.webp" alt="Photo 38">
    <img src="/images/gallery/photo39.webp" alt="Photo 39">
    <img src="/images/gallery/photo40.webp" alt="Photo 40">
    <img src="/images/gallery/photo41.webp" alt="Photo 41">
    <img src="/images/gallery/photo42.webp" alt="Photo 42">
    <img src="/images/gallery/photo43.webp" alt="Photo 43">
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
