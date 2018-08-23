<template>
  <div>
    <p class="card">
      {{text}}
    </p>
  </div>
</template>

<script>
export default {
  props: ["text"]
};
</script>

<style lang="scss" scoped>
$border: #999;

.card {
  padding: 10rpx;
  border: 1rpx solid $border;
  & + .card {
    margin-left: 5rpx;
  }
}
</style>
