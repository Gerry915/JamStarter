<template>
  <section id="header">
    <button>Button</button>
    <h1>JamStart</h1>
    <div class="logo"></div>
  </section>
</template>

<style lang="scss" scoped>
#header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 80px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #000;
  color: white;
}
.logo {
  background: url(/github.svg);
  background-position: center center;
  background-repeat: no-repeat;
  width: 32px;
  height: 32px;
}
button {
  background-color: greenyellow;
  color: black;
  border: none;
  padding: 0.5rem 0.75rem;
  border-radius: 5px;
}
</style>
