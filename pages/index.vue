<template>
  <div class="page">
    <div class="placeholder">COMING SOON</div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="scss" scoped>
@import '~assets/css/colors.scss';
@import '~assets/css/variables.scss';
.page {
  background-color: #313639;
  height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.placeholder {
  color: $white;
  font-size: 2rem;
}
</style>
