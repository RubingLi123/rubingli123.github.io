---
layout: page
title:  
---

<style>

body {
  background: white;
}

.curiosity-section {
  display: flex;
  align-items: flex-start;
  gap: 10px;
  margin-bottom: 70px;
  margin-top: 20px;
  align-self: stretch;
  flex-wrap: wrap;
}


.cropped-image {
  flex: 1 1 30%;
  aspect-ratio: 3 / 4;
  width: 100%;
  max-width: 400px;
  border-radius: 16px;
  background-image: url("/static/img/trove.jpg");
  background-repeat: no-repeat;
  background-color: lightgray;
  background-size: cover;
  background-position: center;
}
  
/* Right side - 2/3 width */
.curiosity-right {
  flex: 1 1 65%;
  max-width: 65%;
  display: flex;
  flex-direction: column;
  gap: 10px;
  position: relative;
}

/* Text content */
.body_text {
  color: #787878;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

h2 {
  color: #000;
  font-size: 18px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
}

/* Image row */
.curiosity-images {
  display: flex;
  gap: 10px;
  position: relative;
}

.curiosity-images img {
  flex: 1 0 0;
  align-self: stretch;
  border-radius: 16px;
}

.image-half {
  flex: 1;
  position: relative;
}

.image-half img {
  width: 100%;
  height: auto;
  border-radius: 12px;
  object-fit: cover;
}

.view-button {
  display: flex;
  padding: 4px 6px;
  justify-content: center;
  align-items: center;
  gap: 10px;
  position: absolute;
  left: 10px;
  bottom: 12px;
  border-radius: 100px;
  background: #FFF;
  font-size: 0.95em;
  text-decoration: none;
  color: #000;
  font-weight: 500;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.hero {
  position: relative;
  padding: 80px 20px;
  text-align: center;
}

.hero-text h1 {
  font-size: 28px;
  color: black;
  font-weight: 700;
  line-height: 1.4;
  max-width: 800px;
  margin: 0 auto;
  z-index: 1;
  position: relative;
}

.hero-text span {
  display: block;
  margin-top: 12px;
  font-weight: 600;
}

/* Decorative Icons */
.decor {
  position: absolute;
  width: 48px;
  height: auto;
  z-index: 0;
}

.icon-pencil {
  left: 0;
  top: 50%;
  transform: translate(-50%, -50%);
}

.icon-music1 {
  left: 30%;
  top: 10%;
}

.icon-mountain {
  left: 50%;
  top: 10px;
  width: 130px;
  transform: translateX(-50%);
}

.icon-flower {
  right: 10%;
  top: 10%;
}

.icon-music2 {
  right: 0;
  bottom: 10%;
  transform: translateX(50%);
}

/* Responsive scaling */
@media (max-width: 768px) {
  .hero-text h1 {
    font-size: 24px;
  }

  .decor {
    width: 32px;
  }
}

.run {
  background: #F5F9FF;
  padding: 40px 40px;
  font-family: sans-serif;
  color: #111;
  max-width: full;
}

.resilience-flex {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 30px;
}

.resilience-image, .resilience-card {
  flex: 1;
  min-width: 280px;
}

.resilience-image {
  width: 508px;
  height: 300px;
  border-radius: 16px;
  background: url("/static/img/marathon.PNG") lightgray 0px 0px / 100% 199.843% no-repeat;
  background-size: cover;
  background-position: center;
}

.resilience-card {
  background-color: #253A71;
  color: white;
  border-radius: 16px;
  padding: 24px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 20px;
}

.resilience-card h3 {
  margin-top: 0;
  margin-bottom: 8px;
}

.bridge-img {
  width: 100%;
  border-radius: 12px;
  object-fit: cover;
}

.music-img {
  width: 100%;
  height: 300px;
  border-radius: 12px;
  background: url("/static/img/music.jpg") lightgray 0px 0px / 100% 199.843% no-repeat;
  background-size: cover;
  background-position: center;
}

</style>

<section class="hero">
  <div class="hero-text">
    <h1>
      Driven by rhythm, resilience, and curiosity<br />
      —in the field, on the run, and through every note.
    </h1>
  </div>

  <!-- Decorative Icons -->
  <img src="/static/icon/pencil.png" class="decor icon-pencil" alt="Pencil icon" />
  <img src="/static/icon/music1.png" class="decor icon-music1" alt="Music icon" />
  <img src="/static/icon/mountain.png" class="decor icon-mountain" alt="Mountain icon" />
  <img src="/static/icon/flower.png" class="decor icon-flower" alt="Flower icon" />
  <img src="/static/icon/music2.png" class="decor icon-music2" alt="Music icon" />
</section>

<div class="curiosity-section">
  <!-- Left Side Image -->
  <div class="cropped-image"></div>
  
  <!-- Right Side: Text + Images -->
  <div class="curiosity-right">
    <div>
      <h2>Curiosity on the Ground</h2>
      <p class="body_text">
        During a recent visit to one of <strong>San Francisco’s largest recommerce warehouses</strong>, I witnessed the complex systems behind recycling pre-owned goods—a hands-on reminder of how <strong>design, logistics, and sustainability</strong> intersect in the real world.
      </p>
    </div>
    <div class="curiosity-images">
      <div class="image-half">
        <img src="/static/img/trove2.jpeg" alt="Sorting station">
        <a class="view-button" href="/recommerce_visits/">View Documentation</a>
      </div>
      <div class="image-half">
        <img src="/static/img/overview.JPG" alt="Trove sign outside">
      </div>
    </div>
  </div>
</div>

<section class="run">
  <h2>Resilience in Every Stride</h2>
  <p class="body_text">
    I ran my first <strong>New York City Marathon</strong> in November 2023, following a
    <strong>structured training program</strong> that sparked my passion for distance running and goal-setting.
  </p>

  <div class="resilience-flex">
    <!-- Left Image -->
    <div class="resilience-image"></div>
    <div class="resilience-card">
      <div class="card-text">
        <h3>Conquering the Queensboro Bridge</h3>
        <p>
          At mile 19, the Queensboro Bridge’s <strong>relentless 5-mile incline</strong> pushed me to my limits— a defining moment in building both mental and physical endurance.
        </p>
      </div>
      <img src="/static/img/bridge.png" alt="Queensboro Bridge" class="bridge-img" />
    </div>
  </div>
</section>

<section class="music">
  <h2>Precision in Harmony</h2>
  <p class="body_text">
    As a <strong>classically trained violinist</strong>, I see every piece as a <strong>layered narrative</strong>, rich in structure and emotion. A highlight was witnessing <strong>Yuja Wang’s Rachmaninoff marathon</strong>—a stunning performance of all five concertos in one night, echoing the <strong>discipline and depth</strong> I bring to my work.
  </p>
  <div class="music-img"></div>
</section>
