<template>
  <header class="header">
    <div class="header__container">
      <LogoCompany/>
      <a href="" class="header__number">+7 987 654 32-10</a>
    </div>
  </header>
</template>

<script>
import LogoCompany from '@/components/icons/LogoCompany.vue'

export default {
  name: 'TheHeader',
  components: {
    LogoCompany
  }
}
</script>

<style lang="scss" scoped>
.header {
  background-color: #3278FF;
  padding: 13px 0px;
  &__container {
    max-width: 1780px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  &__number {
    font-weight: 600;
    color: #fff;
    font-size: 22px;
    line-height: 26px;
  }
}
</style>
