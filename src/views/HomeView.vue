<template>
  <div class="main-container">
    <div class="container">
      <h1 class="head-text">Ali Maher</h1>
      <p class="main-text">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining
        essentially unchanged. It was popularised in the 1960s with the release
        of Letraset sheets containing Lorem Ipsum passages, and more recently
        with desktop publishing software like Aldus PageMaker including versions
        of Lorem Ipsum.
      </p>
    </div>
    <div class="right-container">
      <img src="../pictures/AliMaher.jpg" alt="Avatar" class="photo" />
      <div class="logos-container">
        <a href="mailto:alimohammadmaher@gmail.com">
          <img src="../pictures/mdi_email.svg" alt="email" class="email-logo" />
        </a>
        <a href="https://github.com/aliiimaher/">
          <img
            src="../pictures/bxl_github.svg"
            alt="github"
            class="github-logo"
          />
        </a>
        <!--  -->
        <a href="https://www.linkedin.com/in/aliiii-maher/">
          <img
            src="../pictures/jam_linkedin-circle.svg"
            alt="linkedin"
            class="linkedin-logo"
          />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.main-container {
  max-width: 1600px;
  background-color: #f1f1f1;
  padding: 20px;
  /* display: flex;
  margin: auto;
  margin-left: auto;
  margin-right: auto; */
}

.container {
  max-width: 600px;
  /* height: 100%; */
  background-color: #f1f1f1;
  padding: 20px;
  /* display: flex; */
}

.head-text {
  font-size: 32px;
  font-style: bold;
  font-family: "Times New Roman", Times, serif;
}

.main-text {
  font-size: 24px;
  font-family: "Times New Roman", Times, serif;
}

.right-container {
  justify-content: center;
  position: relative;
  display: flex;
  flex-direction: column;
}

.photo {
  border-radius: 100%;
  width: 320px;
  background-color: #f1f1f1;
  padding: 16px;
  margin: auto;
}

.logos-container {
  display: flex;
  /* justify-content: center; */
  justify-content: space-around;
}

@media screen and (min-width: 800px) {
  .main-container {
    display: flex;
    margin: auto;
    margin-left: auto;
    margin-right: auto;
    /* gap: 400px; */
    justify-content: space-between;
  }
}
</style>
