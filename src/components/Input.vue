<template>
  <div>
    <input type="text" v-model="colorCode" placeholder="Enter Color Code..." />
  </div>
</template>

<script>
export default {
  computed: {
    colorCode: {
      get() {
        return this.$store.state.colorCode;
      },
      set(value) {
        this.$store.dispatch("changeColorCode", value);
      },
    },
  },
};
</script>

<style>
</style>