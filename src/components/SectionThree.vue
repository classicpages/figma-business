<template>
  <section class="section-three">
    <div class="overlay">
      <h1>Over <button>$500 Million</button> Verdicts & Settlements</h1>
    </div>
    <div class="container">
      <!-- Left Side -->
      <div class="left-divs">
        <div class="div-box">$17</div>
        <div class="div-box">$14</div>
        <div class="div-box">$13</div>
      </div>

      <!-- Right Side -->
      <div class="right-divs">
        <div class="div-box">$09</div>
        <div class="div-box">$07</div>
        <div class="div-box">$04</div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionThree'
}
</script>

<style scoped>
.section-three {
  position: relative;
  background-color: #002a7d;
  padding: 40px 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 255, 0.5); /* Transparent 500 */
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.overlay h1 {
  color: white;
  font-size: 24px;
  font-weight: bold;
}

.overlay button {
  background-color: rgb(207, 70, 70);
  color: white;
  border: 2px solid white;
  padding: 10px 20px;
  cursor: pointer;
  font-weight: 800;
  font-size: 24px;
}

.container {
  z-index: 1; /* Make sure divs appear on top of the overlay */
  display: flex;
  justify-content: space-between;
  width: 100%;
  max-width: 1200px;
  padding: 20px;
}

.left-divs .right-divs {
  display: block;
}

.div-box {
  border: 1px solid white;
  color: white;
  font-size: 20px;
  padding: 20px;
  text-align: center;
  margin: 10px 0;
}

/* RESPONSIVENESS */

/* For smaller screens */
@media (max-width: 768px) {
  .container {
    flex-direction: column;
    align-items: center;
  }

  .left-divs,
  .right-divs {
    width: 100%;
  }

  .div-box {
    font-size: 18px;
    padding: 15px;
  }
}
</style>
