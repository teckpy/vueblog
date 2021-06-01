<template>
  <div>
    <h1 v-if="true">Hello from Home Components !</h1>
    <button v-on:click="hello" class="btn btn-primary">
      Call Hello Function
    </button>
  </div>
</template>
<script>
export default {
  name: "Home",
  methods: {
    hello() {
      alert("Hello Function Called !");
    },
    data() {
      return { show: false };
    },
  },
};
</script>