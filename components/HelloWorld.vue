<template>
  <h1 class="hello">Hello Nuxt Community</h1>
</template>

<script>
export default {
    name: 'hello-world'
};
</script>

<style>
  :root{
    --hello-world-text: red;
  }
  .hello {
    color: var(--hello-world-text);
    background-color: var(--hello-world-bg);
  }
</style>
