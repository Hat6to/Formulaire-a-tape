<template>

   <h1>hello</h1>
<ul v-if="show">
  <li v-for="item in items" :key="item.message">
    {{ item.message }}
  </li>
</ul>
 <button v-on:click="show = true">aficher</button>
 <button v-on:click="show = false">cacher</button>

</template>

<script>
export default {
  name: "HelloWorld",
   props: {
    msg: String
},
 data() {  
    return {
      items: [{ message: "Ellyes" }, { message: "Noam" }, { message: "Souri" }, { message: "Romain" }, { message: "Antho" }, ],
      show :true
    };
  }
}
</script>

<style scoped>

</style>
