<template>
  <section id="footer">
    <p>© - {{ fullYear }} Gerry Gao</p>
  </section>
</template>

<script>
export default {
  computed: {
    fullYear() {
      return new Date().getFullYear()
    },
  },
}
</script>

<style lang="scss" scoped>
#footer {
  position: fixed;
  display: flex;
  justify-content: center;
  align-items: center;
  bottom: 0;
  left: 0;
  width: 100vw;
  padding: 1rem 1rem;
  background-color: #000;
  color: white;
}
</style>
