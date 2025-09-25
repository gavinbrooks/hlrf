---
title: "About H-LRF"
banner:
  image: "images/hiroshima_skyline_long.jpg"
  title: "About Us"
  description: "Supporting early-career researchers and PhD students"
type: "page"
---

<div class="about-content">

<section class="card-section left-image">
  <div class="card-container">
    <div class="card-image">
      <img src="{{< relurl "images/hiroshima.png" >}}" alt="Hiroshima" />
    </div>
    <div class="card-text">
      <h2>Our Mission</h2>
      <p>The Hiroshima Lexical Research Forum (H-LRF) is dedicated to advancing research in lexical studies and supporting early-career researchers and PhD students in the field of applied linguistics and language learning.</p>
      <p>Our aim is to support early-career researchers and PhD students with the help of our world experts. We provide a platform for sharing cutting-edge research and fostering collaboration among researchers worldwide.</p>
    </div>
  </div>
</section>

<section class="card-section right-image">
  <div class="card-container">
      <div class="card-image">
      <img src="{{< relurl "images/atomic_domb.jpg" >}}" alt="Peace Memorial Park" />
    </div>
    <div class="card-text">
      <h2>Our Conferences</h2>
      <p>Based in Hiroshima, Japan, we are proud to host a yearly conference that focuses on second-language vocabulary acquisition. We are fortunate to have the support of many established researchers who attend our yearly conference.</p>
      <p>Our environment is supportive and rigorous, catering to researchers at all stages of their careers, from beginners to those with years of experience.</p>
    </div>
  </div>
</section>

</div>

<style>
.about-content {
  max-width: 100%;
  margin: 0 auto;
}

.card-section {
  margin: 3rem 0;
  padding: 0 1rem;
}

.card-container {
  display: flex;
  align-items: stretch;
  gap: 0;
  max-width: 1400px;
  margin: 0 auto;
  background: #f8f9fa;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  position: relative;
}

/* Colored bar at top of card */
.card-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: rgb(98, 0, 234);
  z-index: 1;
}

.card-image {
  flex: 0 0 33.333%;
  display: flex;
  align-items: center;
}

.card-image img {
  width: 100%;
  height: 250px;
  object-fit: cover;
}

.card-text {
  flex: 1;
  padding: 2rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.card-text h2 {
  margin-top: 0;
  margin-bottom: 1rem;
  color: #333;
  font-size: 1.8rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid rgb(98, 0, 234);
  display: inline-block;
}

.card-text p {
  margin-bottom: 1rem;
  line-height: 1.6;
  color: #555;
}

.card-text p:last-child {
  margin-bottom: 0;
}

/* Right image layout */
.right-image .card-container {
  flex-direction: row-reverse;
}

/* Responsive design */
@media (max-width: 1024px) {
  .card-container {
    max-width: 1200px;
  }
}

@media (max-width: 768px) {
  .card-container,
  .right-image .card-container {
    flex-direction: column;
    text-align: center;
  }

  .card-image {
    flex: none;
    width: 100%;
  }

  .card-image img {
    height: 200px;
  }

  .card-text {
    padding: 1.5rem;
  }
}
</style>