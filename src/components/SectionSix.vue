<template>
  <section class="section-six">
    <h2 class="section-title">Testimonials</h2>
    <div class="testimonials-container">
      <!-- First Row (4 divs) -->
      <div class="testimonial-div">
        <h3>Opinions made by our clients</h3>
      </div>
      <div class="testimonial-div">
        <p>
          Planning for the future can be overwhelming, but David made the entire process of estate
          planning smooth and efficient. His attentiveness and genuine care ensured my wishes were
          clearly documented and protected. I have complete peace of mind knowing my family is taken
          care of, thanks to David's exceptional service.
          <br /><br />
          <strong>David Lee | Estate Planning</strong>
        </p>
      </div>
      <div class="testimonial-div">
        <p>
          Facing criminal charges was a terrifying experience. Emily immediately put me at ease with
          her confident and reassuring demeanor. She thoroughly investigated my case, built a strong
          defense strategy, and ensured I understood my options every step of the way.
          <br /><br />
          <strong>Emily Garcia, Criminal Defense</strong>
        </p>
      </div>
      <div class="testimonial-div">
        <p>
          I am writing this letter to express my endless gratitude to you and your staff. After my
          fall I really wondered how I would ever be able to recover for of the damages I suffered.
          All of you worked so fast and kept me informed with everything that was going on. Without
          your help, the insurance company would have taken advantage of me. You got me the justice
          that I feel in my heart that I deserve.
          <br /><br />
          <strong>Katie Miller</strong>
        </p>
      </div>

      <!-- Second Row (4 divs) -->
      <div class="testimonial-div">
        <p>
          I was facing a complex contract dispute with a business partner. Sarah meticulously
          analyzed the situation and guided me through every step of the process. Her clear
          communication and expertise ultimately led to a favorable outcome. I highly recommend
          Sarah to anyone seeking a knowledgeable and dedicated lawyer.
          <br /><br />
          <strong>Sarah Jones | Contract Dispute</strong>
        </p>
      </div>
      <div class="testimonial-div">
        <p>
          Going through a divorce is never easy, but Michael provided invaluable support and
          guidance throughout the process. He was always available to answer my questions and
          advocate for my best interests. He prioritized a fair outcome every time.
          <br /><br />
          <strong>Michael Brown | Family Law</strong>
        </p>
      </div>
      <div class="testimonial-div">
        <p>
          As my business grew, I needed legal guidance to navigate various legal aspects. Jennifer
          has been an invaluable asset, providing comprehensive advice on everything from contracts
          to intellectual property. Her proactive approach and in-depth knowledge have empowered me
          to make informed decisions for my company's success.
          <br /><br />
          <strong>Zhi Hung | Parent of Injury Victim</strong>
        </p>
      </div>
      <div class="testimonial-div">
        <p>
          I am impressed with the way you handled the jury at my trial. I didn’t know so much
          passion could come from someone on my behalf. You really cared about me.
          <br /><br />
          <strong>Stanley Chung | Workplace Injury</strong>
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionSix'
}
</script>

<style scoped>
/* Section background */
.section-six {
  background: rgba(185, 214, 242, 1);
  padding: 40px;
}

/* Title styling */
.section-title {
  text-align: center;
  font-size: 32px;
  margin-bottom: 40px;
  color: #061a40;
}

/* Container for testimonials, ensuring they align next to each other */
.testimonials-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: space-between;
}

/* Individual testimonial divs next to each other */
.testimonial-div {
  background-color: white;
  padding: 20px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  flex: 1 1 calc(50% - 20px); /* Ensures 2 divs per row */
  max-width: 48%; /* Prevents overflow */
  box-sizing: border-box;
}

/* Heading and paragraph styles */
.testimonial-div h3 {
  color: #061a40;
  font-size: 24px;
  margin-bottom: 10px;
}

.testimonial-div p {
  font-size: 16px;
  color: #333;
  line-height: 1.6;
}

/* Strong text styling */
.testimonial-div strong {
  color: #061a40;
  display: block;
  margin-top: 10px;
}

/* RESPONSIVENESS */

/* For smaller screens (mobile) */
@media (max-width: 768px) {
  .testimonial-div {
    flex: 1 1 100%;
    max-width: 100%; /* Stacks the divs on small screens */
  }

  .section-title {
    font-size: 28px;
  }
}

/* For extra small screens */
@media (max-width: 480px) {
  .section-title {
    font-size: 24px;
  }

  .testimonial-div p {
    font-size: 14px;
  }
}
</style>
