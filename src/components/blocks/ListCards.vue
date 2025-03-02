<template>
    <div class="list">
      <BookCard
        title="Skyrim. История создания великой игры"
        subtitle="Франк Экстанази"
        srcImg= "../../assets/image/image 1.png"
      />
      <BookCard
        title="Поисковое продвижение сайтов"
        subtitle="Сергей Анисимов"
        srcImg="../../assets/image/image 2.png"
      />
      <BookCard
        title="Английский для дизайнеров"
        subtitle="Татьяна Магарина"
        srcImg="../../assets/image/image 3.png"
      />
      <BookCard
        title="Дизайн и цвет. Практикум"
        subtitle="Шон Адамс"
        srcImg="../../assets/image/image 4.png"
      />
    </div>
</template>

<script>

import BookCard from '@/components/elements/BookCard.vue'

export default {
  name: 'ListCard',
  components: {
    BookCard
  }
}
</script>

<style lang="scss" scoped>
  .list {
    height: calc(100vh - 66px);
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 26px;
  }
</style>
