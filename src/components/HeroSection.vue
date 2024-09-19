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
      <div class="header-right">+233-257-732-425</div>
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
  background-color: #002a7d;
  color: white;
  background-image: url(/src/assets/Rectangle\ 3.png);
}

.header {
  background-color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: black;
}

.alvin {
  color: #e63946;
  width: 116px;
  height: 43px;
  font-family: 'Sora' sans-serif;
  font-size: 34px;
  font-weight: 800;
  line-height: 42.84px;
  letter-spacing: 0.04em;
  text-align: left;
}

.header-left {
  font-size: 1.2rem;
  font-weight: bold;
  width: 190px;
}

.asso {
  width: 116px;
  height: 18px;
  gap: 0px;
  opacity: 0px;
  font-family: 'Plus Jakarta Sans' sans-serif;
  font-size: 14px;
  font-weight: 700;
  line-height: 17.64px;
  letter-spacing: 0.08em;
  text-align: left;
}

.header-center {
  text-align: center;
}

.contact {
  color: white;
  background-color: red;
  padding-left: 20px;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-right: 20px;
  border: none;
}

.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  gap: 15px;
  height: 32px;
  font-family: 'Roboto' sans-serif;
  font-size: 16px;
  font-weight: 600;
  color: #2e294e;
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
}

.hero-text {
  flex: 1;
}

.hero-text h1 {
  margin-bottom: 20px;
  margin-left: 180px;
  width: 896px;
  height: 348px;
  font-family: 'Plus Jakarta Sans' sans-serif;
  font-size: 92px;
  font-weight: 800;
  line-height: 115.92px;
  text-align: left;
  color: #ffffff;
}

.consultation-button {
  background-color: red;
  color: white;
  padding: 20px 30px;
  border: none;
  margin-left: 180px;
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
