<template>
  <header :class="$style.header">
    <div :class="$style.logo">
      <a href="/">
        <img src="@/assets/logo.svg" alt="" width="100" height="100" />
      </a>
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style lang="scss" module>
.header {
  border-bottom: 0.1rem solid $Border;
  @include flexCenter;
  padding: 1rem 1rem 0 1rem;
  .logo {
    img {
      width: 100%;
    }
  }
}
</style>
