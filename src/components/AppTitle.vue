<script>
export default {
  data() {
    return {
      messaggio: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <h1>{{ messaggio }}</h1>
</template>
<!-- lang="scss" deve essere "installato e te lo chiederà nel momento in cui lo usi ("npm install -D sass")" -->
<style lang="scss" scoped>
h1 {
  color: red;
  text-align: center;
}
</style>
