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
  align-items: stretch;
  gap: 10px;
  margin-bottom: 70px;
  margin-top: 20px;
  align-self: stretch;
  flex-wrap: wrap;
}


.cropped-image {
  flex: 1 1 30%;
  width: 100%;
  height: 400px;
  max-width: 400px;
  border-radius: 16px;
  background-image: url("/static/img/trove.jpg");
  background-repeat: no-repeat;
  background-color: lightgray;
  background-size: cover;
  background-position-x: -90px;
  background-position-y: center;
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

.body_text_white {
  color: white;
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
  height: 200px;
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
  height: 324px;
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
  font-size: 18px;
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
      Thought in tempo, form in focus, research in the real world.
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
      <h2>Behind the Scenes of Recommerce</h2>
      <p class="body_text">
          I recently visited one of the largest recommerce warehouses in San Francisco and was amazed to see the intricate processes behind recycling pre-owned items. Click <a href="/recommerce_visits/">here</a> to see more photos behind the scene!
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
  <h2>Run. Think. Repeat.</h2>
  <p class="body_text">
    I completed my first New York City full marathon in November 2023. I followed a popular marathon training <a href="https://www.halhigdon.com/training/marathon-training/">program</a>, which has since inspired me to pursue more serious running.
  </p>

  <div class="resilience-flex">
    <!-- Left Image -->
    <div class="resilience-image"></div>
    <div class="resilience-card">
      <div class="card-text">
        <h3>Conquering the Queensboro Bridge</h3>
        <p class="body_text_white">
          The most challenging section of the route was the Queensboro Bridge at mile 19, with its grueling 5-mile uphill climb—a true test for a casual runner like me. 
        </p>
      </div>
      <img src="/static/img/bridge.png" alt="Queensboro Bridge" class="bridge-img" />
    </div>
  </div>
</section>

<section class="music">
  <h2>A Symphony in Progress</h2>
  <p class="body_text">
      I am a fan of classical music and a classically trained violinist, appreciating each piece as a delicately crafted novel with a rich, layered structure. Last year, I had the unforgettable experience of attending a Rachmaninoff marathon, where Yuja Wang performed all five piano concertos in a single program!
  </p>
  <div class="music-img"></div>
</section>

   
<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=080808&w=70&t=n&d=O8suamHxmsJ0Q9xPWGTZ-axPrNLubvMXcLlaLEJQwzk&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>
