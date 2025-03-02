<template>
  <button class="btn">{{ name }}</button>
</template>

<script>
export default {
  name: 'BaseButton',
  components: {
  },
  props: {
    name: {
      type: String,
      default: ''
    }
  }
}
</script>

<style lang="scss" scoped>
  .btn {
  background-color: #3278FF;
  color: #ffffff;
  border-radius: 7px;
  padding: 6px 38px;
  font-size: 20px;
  font-weight: 500;
  border: none;
  margin-top: auto;
}
</style>
