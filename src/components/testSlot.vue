<script setup>

</script>

<template>
  <div class="container">
    <header>
      <slot name="header"></slot>
    </header>
    <main>a
      <slot></slot>
    </main>
    <footer>
      <slot name="footer"></slot>
    </footer>
  </div>
</template>

<style scoped>

</style>
