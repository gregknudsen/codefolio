<template>
  <div class="footer">
    <a class="footer__link" href="https://github.com/0xAliRaza/codefolio"
      >Codefolio</a
    >, coded with <Icon name="heart" /> by
    <a class="footer__link" href="#">Greg Knudsen</a> &#169;2024
  </div>
</template>

<style lang="scss" scoped>
@import '@/scss/abstracts';
.footer {
  height: $footer-height;
  vertical-align: center;
  width: 100%;
  background: transparent;
  color: $gray-6;
  font-size: pxToRem(12);
  text-align: center;
  padding: pxToRem(16px) pxToRem(10px) pxToRem(6px);
  &__link {
    color: inherit;
    @include hoctive {
      color: $gray-6;
    }
  }
}
</style>
