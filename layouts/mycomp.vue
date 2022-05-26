<template>
  <div class="slidev-layout wrapper" :class="Class">
    <div class="content">
      <slot />
    </div>
  </div>
</template>

<script>
  export default {
    name: "mycomp",
    props: {
      background: String,
      Class: String
    }
  };
</script>

<style scoped>
  .wrapper {
    background: rgb(63, 58, 58);
  }
</style>
