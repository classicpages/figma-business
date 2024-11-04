<template>
  <div class="hero-section">
    <header class="header">
      <div class="header-left">
        <span class="alvin">ALVIN</span> & <span class="asso">Associate</span>
      </div>
      <div class="header-center">
        <ul class="nav-list">
          <li>Home</li>
          <li>About Us</li>
          <li>Achievement</li>
          <li>Practice Area</li>
          <li>Testimonials</li>
          <li>FAQs</li>
          <button class="contact"><li>Contact Us</li></button>
        </ul>
      </div>
      <div class="header-right">(+233)257732-425</div>
    </header>

    <div class="hero-content">
      <div class="hero-text">
        <h1 class="legal">Legal Excellence, Personalized Service</h1>
        <button class="consultation-button">Request a free consultation</button>
        <div class="hero-frame">
          <img src="/src/assets/Frame 3.png" alt="Frame Image" />
        </div>
      </div>

      <div class="hero-image">
        <img src="/src/assets/1 1.png" alt="Hero Image" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>

<style scoped>
.hero-section {
  color: white;
  background-size: cover;
  background-position: center;
  background-color: rgb(22, 22, 170);
}

.header {
  background-color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: black;
  padding: 10px 20px; /* Added padding for better spacing */
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Added shadow for depth */
}

.alvin {
  color: #e63946;
  font-family: 'Sora', sans-serif;
  font-size: 34px;
  font-weight: 800;
}

.header-left {
  font-size: 1.2rem;
  font-weight: bold;
}

.asso {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-size: 14px;
  font-weight: 700;
}

.header-center {
  text-align: center;
}

.contact {
  color: white;
  background-color: red;
  padding: 10px 20px;
  border: none;
  border-radius: 5px; /* Added border radius for button */
}

.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  gap: 15px;
  font-family: 'Roboto', sans-serif;
  font-size: 16px;
  font-weight: 600;
}

.nav-list li {
  display: inline-block;
}

.header-right {
  font-size: 1rem;
  color: red;
}

.hero-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  flex-wrap: wrap; /* Allow wrapping for smaller screens */
}

.hero-text {
  flex: 1;
  min-width: 300px;
  max-width: 600px; /* Adjusted max width for better layout */
  margin-right: 20px; /* Added margin for spacing */
}

.legal {
  margin-bottom: 20px;
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-size: clamp(2.5rem, 5vw, 4rem); /* Responsive scaling */
  color: #ffffff;
  font-weight: 800;
  line-height: 1.2;
  text-align: left;
}

.consultation-button {
  background-color: red;
  color: white;
  padding: 16px 32px; /* Adjusted padding for better size */
  border: none;
  border-radius: 10px;
  font-size: clamp(1rem, 2.5vw, 1.2rem); /* Responsive font scaling */
  cursor: pointer;
  margin-bottom: 20px; /* Reduced margin for compactness */
}

.hero-frame {
  margin-top: 20px;
  width: 100%;
  max-width: 590px;
  padding: 20px 0;
  gap: 48px;
  border-radius: 10px 10px 0px 0px;
  opacity: 0.6;
}

.hero-image {
  flex: 1;
  min-width: 300px;
  text-align: right; /* Align the image to the right */
}

.hero-image img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
}

@media (max-width: 768px) {
  .hero-content {
    flex-direction: column;
    text-align: center;
  }

  .hero-text {
    margin-right: 0; /* Remove margin for smaller screens */
  }

  .nav-list {
    flex-direction: column;
    gap: 10px;
  }
}

@media (min-width: 481px) and (max-width: 1440px) {
  .hero-text h1 {
    font-size: clamp(1.5rem, 5vw, 2.5rem); /* Responsive font scaling */
  }

  .consultation-button {
    font-size: clamp(0.9rem, 2.5vw, 1rem);
  }

  .hero-content {
    padding: 20px;
  }
}
</style>
