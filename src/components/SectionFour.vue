<template>
  <div class="section-four">
    <!-- Title Section -->
    <h1 class="section-title">Practice Areas</h1>

    <!-- Images and Rectangles Section -->
    <div class="image-flex-container">
      <div class="image-box">
        <img src="/src/assets/Mask group.png" alt="" />
        <div class="box-row">
          <div class="rectangle-box first-box">Car Accidents</div>
          <div class="rectangle-box second-box">Truck Accidents</div>
          <div class="rectangle-box third-box">Dangerous Drugs</div>
        </div>
      </div>

      <div class="image-box">
        <img src="/src/assets/AdobeStock_86156608_Preview 1.png" alt="" />
        <div class="box-row">
          <div class="rectangle-box first-box">Car Accidents</div>
          <div class="rectangle-box second-box">Truck Accidents</div>
          <div class="rectangle-box third-box">Dangerous Drugs</div>
        </div>
      </div>

      <div class="image-box">
        <img src="/src/assets/image 10.png" alt="" />
        <div class="box-row">
          <div class="rectangle-box first-box">Car Accidents</div>
          <div class="rectangle-box second-box">Truck Accidents</div>
          <div class="rectangle-box third-box">Dangerous Drugs</div>
        </div>
      </div>

      <div class="image-box">
        <img src="/src/assets/image 11.png" alt="" />
        <div class="box-row">
          <div class="rectangle-box first-box">Car Accidents</div>
          <div class="rectangle-box second-box">Truck Accidents</div>
          <div class="rectangle-box third-box red-box">Dangerous Drugs</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Section styling */
.section-four {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #002a7d;
  padding: 50px 20px;
}

/* Title styling */
.section-title {
  background-color: #002a7d;
  color: white;
  font-size: 36px;
  text-align: center;
  width: 100%;
}

/* Images Flex Container */
.image-flex-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 20px;
}

/* Individual Image Box */
.image-box {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.image-box img {
  width: 100%;
  max-width: 250px;
  height: auto;
}

/* Rectangle Boxes under Images */
.box-row {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.rectangle-box {
  width: 250px;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 18px;
  color: white;
  text-align: center;
}

.first-box {
  background-color: #9cb4cc;
}

.second-box {
  background-color: rgba(175, 203, 229, 1);
}

.third-box {
  background-color: #c3e1ff;
}

/* Specific Styling for the Red Box under Fourth Image */
.red-box {
  background-color: red;
  color: white;
}

/* Responsiveness */
@media (max-width: 1200px) {
  .rectangle-box {
    width: 400px;
  }
}

@media (max-width: 1024px) {
  .rectangle-box {
    width: 350px;
  }
}

@media (max-width: 900px) {
  .rectangle-box {
    width: 300px;
  }
}

@media (max-width: 768px) {
  .image-flex-container {
    flex-direction: column;
    align-items: center;
  }

  .rectangle-box {
    width: 250px;
  }
}

@media (max-width: 480px) {
  .rectangle-box {
    width: 200px;
  }
}
</style>
