<template>
  <section class="section-nine">
    <p class="footer-text">
      © Phill & Associates 2024. All rights reserved.
      <a href="#" class="footer-link">Privacy Policy</a>
      <span class="divider">|</span>
      <a href="#" class="footer-link">Disclaimer</a>
    </p>
  </section>
</template>

<style scoped>
.section-nine {
  background: rgba(3, 15, 36, 1);
  width: 100%;
  padding: 20px 0;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.footer-text {
  color: white;
  font-size: 16px;
  line-height: 1.5;
  max-width: 1200px;
  margin: 0;
}

.footer-link {
  color: #1e90ff;
  text-decoration: none;
  margin: 0 5px;
}

.footer-link:hover {
  text-decoration: underline;
}

.divider {
  margin: 0 8px;
  color: white;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .footer-text {
    font-size: 14px;
  }

  .divider {
    margin: 0 5px;
  }
}

@media (max-width: 480px) {
  .footer-text {
    font-size: 12px;
  }

  .divider {
    margin: 0 3px;
  }
}
</style>
