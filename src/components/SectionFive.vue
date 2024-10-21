<template>
  <section class="section-five">
    <div class="content-container">
      <!-- First Div: Text Content with Button -->
      <div class="text-div">
        <h2>Personal Injury Damages</h2>
        <p>
          The damages that an injured person can seek compensation for depend on the severity of
          their injuries and the consequences of the incident. Catastrophic injuries, such as those
          affecting the brain, spine, or limbs permanently, may require lifelong care, special
          accommodations, and equipment. In Texas, a knowledgeable attorney can help pursue economic
          and non-economic damages in a personal injury claim. Economic damages cover objective
          financial losses like medical expenses, lost wages, and property damage. Non-economic
          damages are more subjective and may include pain and suffering, loss of affection, and
          emotional distress. Various factors determine the value of non-economic damages including
          age, ability to perform basic tasks, severity of physical pain and mental anguish, prior
          health status, and any resulting temporary or permanent disability.
          <br /><br />
          <strong>The victim’s age</strong><br />
          <strong>The victim’s ability to perform basic tasks</strong><br />
          <strong>Severity of physical pain and mental anguish</strong><br />
          <strong>The Victim’s prior health status</strong><br />
          <strong>Any resulting temporary or permanent disability</strong><br />
          <strong>Area of injury</strong>
        </p>
        <button class="read-more">Read More</button>
      </div>

      <!-- Second Div: Text and Image Blocks -->
      <div class="right-content">
        <div class="info-div">
          <p>
            Unlike many other states, Pennsylvania does not impose a cap on damages unless the
            plaintiff is suing a government entity. The cap is $250,000 if suing the Commonwealth
            and $500,000 for local government.
          </p>
        </div>

        <!-- Third Div: Image -->
        <div class="image-div">
          <img src="/src/assets/Rectangle 25.png" alt="Personal Injury Image" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionFive'
}
</script>

<style scoped>
.section-five {
  background-color: #f5f5f5;
}

.content-container {
  display: flex;
  justify-content: space-between;
}

.text-div {
  width: 60%;
  padding-left: 35px;
  padding-right: 35px;
  background-color: #061a40;
  color: #fff;
}

.text-div h2 {
  font-size: 24px;
  color: #fff;
}

.text-div p {
  font-size: 16px;
  line-height: 1.6;
  color: #b9d6f2;
}

.read-more {
  background-color: red;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  font-weight: bold;
}

.right-content {
  width: 35%;
  display: flex;
  flex-direction: column;
}

.info-div {
  margin-bottom: 0px;
  margin-top: 0px;
  font-family: 'Plus Jakarta Sans' sans-serif;
  font-size: 42px;
  line-height: 63px;
  text-align: left;
}

.info-div p {
  font-size: 25px;
  font-weight: 500;
  color: #333;
  line-height: 1.5;
  background: linear-gradient(180deg, #006daa 0%, #005d91 100%);
}

.image-div img {
  width: 100%;
  height: auto;
  margin-top: 0px;
}

/* RESPONSIVENESS */

/* For smaller screens */
@media (max-width: 768px) {
  .content-container {
    flex-direction: column;
  }

  .text-div {
    width: 100%;
  }

  .right-content {
    width: 100%;
  }

  .read-more {
    width: 100%;
    text-align: center;
  }
}

@media (max-width: 480px) {
  .text-div h2 {
    font-size: 20px;
  }

  .text-div p,
  .info-div p {
    font-size: 14px;
  }

  .read-more {
    font-size: 14px;
    padding: 8px 16px;
  }
}
</style>
