<template>
  <footer class="footer-section">
    <div class="footer-content">
      <!-- Alvin and Associates Section -->
      <div class="company-info">
        <h2 class="company-name">
          <span class="company-name-red">Alvin</span>
          <span class="company-name-white">Associates</span>
        </h2>
        <button class="contact-button">Contact Us</button>
      </div>

      <!-- Contact Information Section -->
      <div class="contact-info">
        <p class="need-help">Need help?</p>
        <p class="phone-number">(+233) 257-732-425</p>
        <address class="address">
          Phil & Associates, P.A.<br />
          897000 Market Street, Suite 99876,<br />
          Texex, Pa 19103<br />
          <a href="#" class="get-directions">Get Directions</a>
        </address>
      </div>

      <!-- Navigation Links Section -->
      <div class="nav-links">
        <a href="#" class="nav-link">Home</a>
        <a href="#" class="nav-link">Our Attorneys</a>
        <a href="#" class="nav-link">About Us</a>
        <a href="#" class="nav-link">Practice Areas</a>
        <a href="#" class="nav-link">Our Success</a>
        <a href="#" class="nav-link">Contact Us</a>
      </div>

      <!-- Image Section -->
      <div class="footer-image">
        <img src="/src/assets/Rectangle 34.png" alt="Footer Image" />
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer-section {
  background: rgba(6, 26, 64, 1);
  width: 100%;
  padding: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.footer-content {
  display: flex;
  flex-wrap: wrap;
  max-width: 1500px;
  width: 100%;
  gap: 20px;
  justify-content: space-around;
}

.company-info {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 10px;
  flex: 1;
  min-width: 250px;
}

.company-name {
  font-size: 24px;
  font-weight: bold;
  margin: 0;
}

.company-name-red {
  color: red;
}

.company-name-white {
  color: white;
}

.contact-button {
  width: 144px;
  height: 28px;
  background-color: red;
  color: white;
  border: none;
  cursor: pointer;
}

.contact-info {
  display: flex;
  flex-direction: column;
  flex: 1;
  min-width: 250px;
}

.need-help,
.phone-number,
.address {
  color: white;
  margin: 0;
}

.get-directions {
  color: white;
  text-decoration: underline;
  cursor: pointer;
}

.nav-links {
  display: flex;
  flex-direction: column;
  gap: 5px;
  flex: 1;
  min-width: 150px;
}

.nav-link {
  color: white;
  text-decoration: none;
}

.footer-image {
  flex: 1;
  min-width: 250px;
  display: flex;
  justify-content: center;
}

.footer-image img {
  width: 100%;
  max-width: 605px;
  height: auto;
  border-radius: 10px 0 0 0;
}

@media (max-width: 768px) {
  .footer-content {
    flex-direction: column;
    align-items: center;
  }

  .company-info,
  .contact-info,
  .nav-links,
  .footer-image {
    align-items: center;
    text-align: center;
    min-width: auto;
  }

  .company-name {
    font-size: 20px;
  }

  .contact-button {
    width: 100px;
    height: 24px;
  }

  .footer-image img {
    max-width: 300px;
  }
}

@media (max-width: 480px) {
  .company-name {
    font-size: 18px;
  }

  .contact-button {
    width: 80px;
    height: 22px;
  }

  .footer-image img {
    max-width: 250px;
  }
}
</style>
