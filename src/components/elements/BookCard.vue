<template>
  <div class="card">
    <img :src="srcImg" alt="" class="card__image">
    <h2 class="card__title">{{ title }}</h2>
    <p class="card__subtitle">{{ subtitle }}</p>
    <BaseButton name="Купить"/>
  </div>
</template>

<script>

import BaseButton from '@/components/ui/BaseButton.vue'

export default {
  name: 'BookCard',
  components: {
    BaseButton
  },
  props: {
    title: {
      type: String,
      default: ''
    },
    subtitle: {
      type: String,
      default: ''
    },
    srcImg: {
      type: String,
      default: ''
    }
  }
}
</script>

<style lang="scss" scoped>
  .card {
    box-shadow: 1px 1px 4px 0px #0000004D;
    width: 290px;
    height: 450px;
    border-radius: 10px;
    text-align: center;
    padding: 15px;
    display: flex;
    flex-direction: column;
    align-items: center;

    &__title {
      font-size: 24px;
      font-weight: 400;
      line-height: 28px;
      margin-bottom: 14px;
    }

    &__subtitle {
      font-size: 20px;
      line-height: 40px;
    }
  }
</style>
