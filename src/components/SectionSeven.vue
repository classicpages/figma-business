<template>
  <section class="section-seven">
    <div class="content-container">
      <!-- Left div (Free Consultation form) -->
      <div class="consultation-form">
        <h2>Free Consultation</h2>
        <p>Fill out the form below to receive a free and confidential initial consultation</p>
        <form>
          <label for="full-name">Full Name:</label>
          <input type="text" id="full-name" placeholder="Enter your full name" required />

          <label for="email">Email:</label>
          <input type="email" id="email" placeholder="Enter your email" required />

          <label for="phone">Phone:</label>
          <input type="tel" id="phone" placeholder="Enter your phone number" required />

          <label for="description">Brief description of your case:</label>
          <textarea
            id="description"
            placeholder="Enter a brief description"
            rows="4"
            required
          ></textarea>

          <button type="submit" class="submit-button">Submit</button>
        </form>
      </div>

      <!-- Right div (FAQs) -->
      <div class="faq-section">
        <h2>FAQs</h2>
        <div class="faq-item">
          <input type="checkbox" id="faq1" />
          <label for="faq1">What is personal injury law and how does it apply to my case?</label>
          <p>
            Personal injury law allows a person to file a civil lawsuit in court to recover damages
            and losses after another party causes them harm. There are a number of situations where
            personal injury law may apply, such as car accidents, slip and fall accidents, medical
            malpractice, dog bites, defective products, etc.
          </p>
        </div>
        <div class="faq-item">
          <input type="checkbox" id="faq2" />
          <label for="faq2">How do I know if I have a valid personal injury claim in Texas?</label>
        </div>
        <div class="faq-item">
          <input type="checkbox" id="faq3" />
          <label for="faq3">How much compensation can I recover for my personal injury case?</label>
        </div>
        <div class="faq-item">
          <input type="checkbox" id="faq4" />
          <label for="faq4"
            >How long do I have to file a personal injury lawsuit in Pennsylvania?</label
          >
        </div>
        <div class="faq-item">
          <input type="checkbox" id="faq5" />
          <label for="faq5">What are the common types of personal injury cases in Texas?</label>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionSeven'
}
</script>

<style scoped>
/* Section background */
.section-seven {
  background: rgba(185, 214, 242, 1);
  padding: 40px;
}

/* Flex container to hold both divs */
.content-container {
  display: flex;
  justify-content: space-between;
  gap: 40px;
  align-items: flex-start;
}

/* Consultation Form */
.consultation-form {
  flex: 1;
  background-color: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.consultation-form h2 {
  font-size: 24px;
  margin-bottom: 10px;
  color: rgba(3, 83, 164, 1);
}

.consultation-form p {
  margin-bottom: 20px;
  color: #333;
}

.consultation-form label {
  display: block;
  margin-bottom: 5px;
  color: rgba(3, 83, 164, 1);
}

.consultation-form input,
.consultation-form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.consultation-form .submit-button {
  width: 100%;
  padding: 10px;
  background-color: red;
  color: white;
  border: none;
  border-radius: 4px;
  font-size: 16px;
  cursor: pointer;
}

.consultation-form .submit-button:hover {
  background-color: darkred;
}

/* FAQ Section */
.faq-section {
  flex: 1;
  background-color: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.faq-section h2 {
  font-size: 24px;
  margin-bottom: 10px;
  color: rgba(3, 83, 164, 1);
}

.faq-item {
  margin-bottom: 20px;
}

.faq-item input[type='checkbox'] {
  margin-right: 10px;
}

.faq-item label {
  color: rgba(3, 83, 164, 1);
  font-weight: bold;
}

.faq-item p {
  margin-top: 5px;
  color: #333;
  line-height: 1.5;
}

/* No block, keep the divs in flex layout on all screen sizes */
@media (max-width: 768px) {
  .content-container {
    flex-direction: column;
    gap: 20px;
  }
}
</style>
