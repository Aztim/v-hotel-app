<template>
  <section class="not-found">
    <div class="container">
      <div class="not-found__wrapper">
        <p class="title">Page Not Found</p>
        Back to <a href="/">main page</a>
        <!-- <nuxt-link to="/"> Back to main page </nuxt-link> -->
      </div>
    </div>
  </section>
</template>

<style lang="scss">
.not-found__wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  width: 100%;
  height: 90vh;
  font-weight: bold;
  color: red;
}
</style>
