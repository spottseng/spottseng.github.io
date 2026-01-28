---
layout: page
title: About
subtitle: Hi, I'm Shelby
cover-img: /assets/img/maroon_bells.jpg
---

I work in the data space, building systems that help turn ideas into useful, real-world solutions. What started as an unexpected interest during school quickly became something I genuinely enjoy — especially the mix of problem-solving and creativity involved.

I like to stay curious through side projects and personal experimentation. Outside of tech, I enjoy staying active, listening to music, reading, and hanging out with my dog.

<style>
  * {
    box-sizing: border-box;
  }

  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 10px;
    padding: 10px;
    max-width: 1200px;
    margin: 0 auto;
  }

  .gallery img {
    width: 100%;
    height: 330px; /* fixed tile height */
    object-fit: cover; /* crops to fill space nicely */
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
    cursor: pointer;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .gallery img:hover {
    transform: scale(1.03);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.25);
  }

  /* Lightbox overlay */
  .lightbox {
    display: none;
    position: fixed;
    z-index: 999;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.8);
    justify-content: center;
    align-items: center;
  }

  .lightbox img {
    max-width: 90%;
    max-height: 80%;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(255, 255, 255, 0.2);
  }

  .lightbox:target {
    display: flex;
  }

  .close {
    position: fixed;
    top: 20px;
    right: 30px;
    color: white;
    font-size: 40px;
    text-decoration: none;
    font-weight: bold;
  }

  .close:hover {
    color: #ccc;
  }
</style>

<div class="gallery">
  <a href="#img1"><img src="https://smpotts.github.io/assets/img/tennis_balls.jpg" alt="Sulley with tennis balls"></a>
  <a href="#img2"><img src="https://smpotts.github.io/assets/img/dirty_sulley.jpg" alt="Sulley after playing"></a>
  <a href="#img3"><img src="https://smpotts.github.io/assets/img/sulley_smirk.jpg" alt="Sulley smirking"></a>
  <a href="#img4"><img src="https://smpotts.github.io/assets/img/sulley_field.jpg" alt="Sulley in the field"></a>
  <a href="#img5"><img src="https://smpotts.github.io/assets/img/sulley_shelf.jpg" alt="Sulley on a shelf"></a>
  <a href="#img6"><img src="https://smpotts.github.io/assets/img/voodoo.jpg" alt="Sulley with a toy"></a>
</div>

<!-- Lightbox -->
<div id="img1" class="lightbox"><a href="#" class="close">&times;</a><img src="https://smpotts.github.io/assets/img/tennis_balls.jpg"></div>
<div id="img2" class="lightbox"><a href="#" class="close">&times;</a><img src="https://smpotts.github.io/assets/img/dirty_sulley.jpg"></div>
<div id="img3" class="lightbox"><a href="#" class="close">&times;</a><img src="https://smpotts.github.io/assets/img/sulley_smirk.jpg"></div>
<div id="img4" class="lightbox"><a href="#" class="close">&times;</a><img src="https://smpotts.github.io/assets/img/sulley_field.jpg"></div>
<div id="img5" class="lightbox"><a href="#" class="close">&times;</a><img src="https://smpotts.github.io/assets/img/sulley_shelf.jpg"></div>
<div id="img6" class="lightbox"><a href="#" class="close">&times;</a><img src="https://smpotts.github.io/assets/img/voodoo.jpg"></div>
