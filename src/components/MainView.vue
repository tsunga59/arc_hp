<script setup>
</script>

<template>
  <div id="main-view" class="main-view">
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
</template>

<style lang="scss" scoped>
.main-view {
  text-align: center;
  width: 85%;
  padding: 2rem;
  margin: 4rem auto;
}
.main-text {
  color: #000;
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
    color: #000;
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
