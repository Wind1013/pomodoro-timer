<template>
  <timer-el />
</template>

<script>
import TimerEl from "./components/TimerEl.vue";
export default {
  name: "App",
  components: {
    TimerEl,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Lobster", cursive;
  color: #f85959;
}
#app {
  background: #fff8ee;
}
</style>
