<template>
    <DateInput msg="" />
    <MenuRadio msg="" />
    <SubmitInput msg="" />
</template>

<script>
import DateInput from "./components/DateInput.vue";
import MenuRadio from "./components/MenuRadio.vue";
import SubmitInput from "./components/SubmitInput.vue";

export default {
  name: "App",
  components: {
    DateInput,
    MenuRadio,
    SubmitInput,
  },
  data() {
    return {
      colorie: 'red',
      step: 'step1'
    }
  }
};
</script>

<style>
.temp {
  margin: 1em;
}
</style>