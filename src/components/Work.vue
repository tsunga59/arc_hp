<script setup>
</script>

<template>
  <div id="work" class="work">
    <div class="container">
      <h2 class="sub_title">Work</h2>
      <ul class="work_area">
        <li class="work_list">
          <div class="img_area">
            Image
          </div>
          <div class="text_area">
            <p class="work_title">Title</p>
            <p class="work_text">
              Text Text Text
            </p>
          </div>
        </li>
        <li class="work_list">
          <div class="img_area">
            Image
          </div>
          <div class="text_area">
            <p class="work_title">Title</p>
            <p class="work_text">
              Text Text Text
            </p>
          </div>
        </li>
        <li class="work_list">
          <div class="img_area">
            Image
          </div>
          <div class="text_area">
            <p class="work_title">Title</p>
            <p class="work_text">
              Text Text Text
            </p>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.work {
  text-align: center;
}
.container {
  width: 100%;
  padding: 6rem;
  box-sizing: border-box;
}
.sub_title {
  font-size: 2rem;
  letter-spacing: .2rem;
  margin-bottom: 4rem;
}
.work_area {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.work_list {
  width: 33%;
  margin: auto 1rem;
  .img_area {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 150px;
    padding: 2rem;
    background-color: #f0f0f0;
  }
  .text_area {
    color: #fff;
    background-color: #0f0f0f;
    padding: 2rem;
    .work_title {
      font-size: 1.2rem;
      font-weight: bold;
      margin-bottom: .6rem;
    }
  }
}
</style>
