<template>
  <section class="section-two">
    <div class="content">
      <h1>Texas Personal Injury Lawyer</h1>
      <p>
        Regardless of what caused it, a severe injury has the potential to greatly impact your life.
        It can lead to temporary or permanent disability, substantial medical costs, and potential
        loss of employment and income. In such circumstances, seeking the help of a skilled lawyer
        may be necessary in order to regain financial stability. If your injury was a result of
        someone else's reckless or negligent behavior, engaging the services of a Texas personal
        injury attorney can assist you in pursuing rightful compensation for the harm you have
        endured.
      </p>
      <button>Read More</button>
    </div>
    <div class="images">
      <img class="main-image" src="/src/assets/new-main-image.png" alt="Main Image" />
      <div class="small-images">
        <img src="/src/assets/pic1.png" alt="Small Image 1" />
        <img src="/src/assets/pic2.png" alt="Small Image 2" />
        <img src="/src/assets/pic3.png" alt="Small Image 3" />
        <img src="/src/assets/pic4.png" alt="Small Image 4" />
        <img src="/src/assets/pic5.png" alt="Small Image 5" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionTwo'
}
</script>

<style scoped>
.section-two {
  display: flex;
  flex-wrap: wrap;
  background-color: #007bff; /* Blue background */
  color: white;
  padding: 20px;
  justify-content: center;
}

.content {
  flex: 1;
  max-width: 600px;
  margin: 20px;
}

h1 {
  font-size: 32px;
  margin-bottom: 20px;
}

p {
  font-size: 18px;
  margin-bottom: 20px;
}

button {
  background-color: red;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
  font-size: 16px;
}

.images {
  flex: 1;
  max-width: 600px;
  margin: 20px;
}

.main-image {
  width: 100%;
  height: auto;
  margin-bottom: 20px;
}

.small-images {
  display: flex;
  justify-content: space-between;
}

.small-images img {
  width: calc(20% - 10px);
  height: auto;
}

@media (max-width: 768px) {
  .section-two {
    flex-direction: column;
  }

  .content,
  .images {
    max-width: 100%;
  }

  .small-images {
    flex-wrap: wrap;
  }

  .small-images img {
    width: calc(50% - 10px);
    margin-bottom: 10px;
  }
}
</style>
