<template>
  <div id="app">
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./main/Calculator";

export default {
  name: "App",
  components: { Calculator },
};
</script>

<style>
#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}

body {
  margin: 0;
}
</style>
