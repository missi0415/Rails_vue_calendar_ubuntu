<template>
  <div id="app">
    <Calendar />
    <!-- messageの値を渡す -->
  </div>
</template>

<script>
import Calendar from "./components/Calendar.vue";

export default {
  name: "App",
  components: {
    Calendar
  }
};
</script>
