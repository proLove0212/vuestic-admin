<template>
  <div class="made-by-component text--center pb-3">
    <span>
      ©2019. Made by
      <a href="https://epicmax.co" class="link">Epicmax</a>
    </span>
  </div>
</template>

<script>
export default {
  name: 'made-by',
}
</script>

<style lang="scss">
.made-by-component {
  width: 100%;
  position: absolute;
  bottom: 0;
  color: $white;
}
</style>
