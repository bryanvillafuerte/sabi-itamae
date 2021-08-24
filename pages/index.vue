<template>
  <div class="container-fluid">
    <div>
      <h1>
        SABI ITAMAE
      </h1>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

.container-fluid {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: $color-dark-default;
  
  h1 {
    color: $color-primary-default;
  }
}
</style>
