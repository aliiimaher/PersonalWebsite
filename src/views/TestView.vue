<template>
  <h2>Media Queries</h2>
  <p>Resize the browser window.</p>

  <p>Make sure you reach the breakpoint at 800px when resizing this frame.</p>

  <div class="whole">
    <div class="left">
      <p>Left Menu</p>
    </div>

    <div class="main">
      <p>Main Content</p>
    </div>

    <div class="right">
      <p>Right Content</p>
    </div>
  </div>
</template>

<style scoped>
* {
  box-sizing: border-box;
  text-align: center;
}

.whole {
  display: flex;
  justify-content: center;
}

.left {
  background-color: #2196f3;
  padding: 20px;
  float: left;
  width: 10%; /* The width is 20%, by default */
}

.main {
  background-color: #f1f1f1;
  padding: 20px;
  float: left;
  width: 30%; /* The width is 60%, by default */
}

.right {
  background-color: #04aa6d;
  padding: 20px;
  float: left;
  width: 10%; /* The width is 20%, by default */
}

/* Use a media query to add a break point at 800px: */
@media screen and (max-width: 800px) {
  .left,
  .main,
  .right,
  .whole {
    width: 100%; /* The width is 100%, when the viewport is 800px or smaller */
  }
}
</style>
