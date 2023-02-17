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
    <div>
      <img src="../pictures/AliMaher.jpg" alt="Avatar" class="photo" />
      <div class="logos-container">
        
      </div>
    </div>
  </div>
  <!-- <div class="home">
    <img alt="aliMaher" src="../pictures/AliMaher.jpg" class="img" />
  </div> -->
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.main-container {
  max-width: 1600px;
  /* height: auto; */
  background-color: #f1f1f1;
  padding: 20px;
  display: flex;
  margin: auto;
  margin-left: auto;
  margin-right: auto;
}

.container {
  width: 600px;
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

.photo {
  border-radius: 100%;
  width: 320px;
  background-color: #f1f1f1;
  padding: 20px;
  margin-left: 400px;
}

.logos-container {

}
</style>
