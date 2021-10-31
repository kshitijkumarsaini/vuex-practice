<template>
    <div class="counterSquared">
      {{ $store.state.counter }} 
      <sup>2</sup> = 
      {{ $store.getters.counterSquared }}
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>