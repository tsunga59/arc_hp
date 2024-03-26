<script setup>
</script>

<template>
  <div id="main-view" class="main-view">
    <div class="container">
      <p class="main-text en">
        From Ambition to Realization, We Commit to Your Dreams.
      </p>
      <p class="main-text jp">
        野心から実現へ、我々はあなたの夢にコミットします。
      </p>
      <h1 class="main-logo">
        ARC Co.
      </h1>
      <div class="contact-btn">
        <a href="#contact">
          Contact
        </a>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.main-view {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100vh;
}
.container {
  width: 100%;
  padding: 6rem;
  box-sizing: border-box;
}
.main-text {
  &.en {
    font-size: 1.6rem;
    margin-bottom: .4rem;
  }
  &.jp {
    font-size: 1.3rem;
  }
}
.main-logo {
  font-size: 2rem;
  letter-spacing: .2rem;
  margin-top: 4rem;
}
.contact-btn {
  margin-top: 4rem;
  a {
    display: inline-block;
    font-size: 1.2rem;
    letter-spacing: .2rem;
    border: 1px solid #000;
    padding: 1rem 4rem;
    &:hover {
      color: #fff;
      background-color: #000;
      transition: all .3s;
    }
  }
}
</style>
