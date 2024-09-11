<template>
  <div class="hero-section">
    <header class="header">
      <div class="header-left">ALVIN & Associate</div>
      <div class="header-center">
        <ul class="nav-list">
          <li>Home</li>
          <li>About Us</li>
          <li>Achievement</li>
          <li>Practice Area</li>
          <li>Testimonials</li>
          <li>FAQs</li>
          <li>Contact Us</li>
        </ul>
      </div>
      <div class="header-right">+233257732425</div>
    </header>
    <div class="hero-content">
      <div class="hero-text">
        <h1>Legal Excellence, Personalized Service</h1>
        <button class="consultation-button">Request a free consultation</button>
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
  background-color: #007bff;
  color: white;
  padding: 20px;
}

.header {
  background-color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  color: black;
}

.header-left {
  font-size: 1.2rem;
  font-weight: bold;
}

.header-center {
  text-align: center;
}

.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  gap: 15px;
}

.nav-list li {
  display: inline-block;
}

.header-right {
  font-size: 1rem;
}

.hero-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
}

.hero-text {
  flex: 1;
}

.hero-text h1 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.consultation-button {
  background-color: red;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 1rem;
  cursor: pointer;
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
    margin-bottom: 20px;
  }

  .nav-list {
    flex-direction: column;
    gap: 10px;
  }
}

@media (min-width: 481px) and (max-width: 1440px) {
  .hero-text h1 {
    font-size: 1.5rem;
  }

  .consultation-button {
    font-size: 0.9rem;
  }

  .hero-content {
    padding: 10px;
  }
}
</style>
