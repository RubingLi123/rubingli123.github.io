---
layout: page
title: Misc
---

<style>
.curiosity-section {
  display: flex;
  align-items: flex-start;
  gap: 20px;
  align-self: stretch;
  flex-wrap: wrap;
}

/* Left side - 1/3 width */
.curiosity-left {
  flex: 1 1 30%;
  max-width: 30%;
}

.curiosity-left img {
  width: 100%;
  border-radius: 16px;
  object-fit: cover;
}

/* Right side - 2/3 width */
.curiosity-right {
  flex: 1 1 65%;
  max-width: 65%;
  display: flex;
  flex-direction: column;
  gap: 20px;
  position: relative;
}

/* Text content */
.curiosity-text {
  color: #787878;
  font-family: "Open Sans";
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

.curiosity-text h2 {
  color: #000;
  font-family: "Open Sans";
  font-size: 32px;
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
  background: url(<path-to-image>) lightgray -108.991px 0px / 175.685% 100% no-repeat;
}

.curiosity-images .image-half {
  flex: 1;
  position: relative;
}

.view-button {
  display: flex;
  padding: 12px 16px;
  justify-content: center;
  align-items: center;
  gap: 10px;
  position: absolute;
  left: 14px;
  bottom: 20px;
  border-radius: 100px;
  background: #FFF;
  font-size: 0.95em;
  text-decoration: none;
  color: #000;
  font-weight: 500;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
</style>

<div class="curiosity-section">
  <!-- Left Side Image -->
  <div class="curiosity-left">
    <img src="/static/img/trove.jpeg" alt="Warehouse team photo">
  </div>

  <!-- Right Side: Text + Images -->
  <div class="curiosity-right">
    <div class="curiosity-text">
      <h2>Curiosity on the Ground</h2>
      <p>
        During a recent visit to one of <strong>San Francisco’s largest recommerce warehouses</strong>, I witnessed the complex systems behind recycling pre-owned goods—a hands-on reminder of how <strong>design, logistics, and sustainability</strong> intersect in the real world.
      </p>
    </div>
    <div class="curiosity-images">
      <div class="image-half">
        <img src="/static/img/trove2.jpeg" alt="Sorting station">
        <a class="view-button" href="/recommerce_visits/">View Documentation</a>
      </div>
      <div class="image-half">
        <img src="/static/img/trove3.jpg" alt="Trove sign outside">
      </div>
    </div>
  </div>
</div>
