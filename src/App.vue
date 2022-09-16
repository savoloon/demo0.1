<template>
  <h2>Спасибо, что зашли на мой github</h2>
  <div>
    <button @click="addClicks">Clicks</button>
    <strong style="margin-left: 10px">{{ clicks }}</strong>
  </div>
</template>

<script>

export default {
  data() {
    return {
      clicks: 0
    }
  },
  methods: {
    addClicks() {
      this.clicks += 1;
    }
  }
}
</script>

<style>

</style>
