<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {
      messaggio: "ciao mondo",
    };
  },

  components: { AppTitle, AppHero },
};
</script>

<template>
  <AppTitle />

  <AppHero />
</template>
<!-- lang="scss" deve essere "installato e te lo chiederà nel momento in cui lo usi ("npm install -D sass")" -->
<style lang="scss"></style>
