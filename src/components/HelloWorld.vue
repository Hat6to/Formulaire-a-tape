<template>

  <ul>
  <li v-for="item in items" :key="item.message">
    {{ item.message }}
  </li>
</ul>

</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      items: [{ message: "Ellyes" }, { message: "Noam" }, { message: "Souri" }, { message: "Romain" }, { message: "Antho" }, ],
    };
  },
};
</script>

<style scoped>

</style>
