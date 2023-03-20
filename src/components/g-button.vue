<template>
  <div>
    <button class="g-button">按钮</button>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>
@import '../assets/style/vars.scss';
.g-button{
  font-size: $font-size;
  height: $button-height;
  padding: 0 1em;
  font: inherit;
  border-radius: $border-radius;
  border: 1px solid $border-color;
  background: $button-bg;
}

.g-button:hover{
  border-color:$border-color-hover
}

.g-button:active{
  background: $button-active-bg;
}
</style>