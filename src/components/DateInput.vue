<template>
  <div class="temp">
    <p>Select a day :</p>
    <label for="Date"></label>
    <input type="date" name="date" id="date" />
  </div>
</template>

<script>
export default {
  name: "DateInput",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
</style>
