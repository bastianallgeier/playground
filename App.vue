<template>
  <div>
    {{ message }}
  </div>
</template>

<script>
export default {
  data() {
    return {
        message: "Hello world"
    };
  }
};
</script>

<style lang="scss">
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-family: -apple-system, sans-serif;
}

body {
  margin: 3rem;
}
</style>
