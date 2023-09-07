<script>
export default {
  data() {
    return {
      image: "hello-world.jpg",
    };
  },

  methods: {
    imageGenerate(imageName) {
      const imageUrl = new URL("../assets/img/" + imageName, import.meta.url);

      return imageUrl.href;
    },
  },
};
</script>

<template>
  <div class="img-center">
    <img :src="imageGenerate(image)" alt="" />
  </div>
</template>
<!-- lang="scss" deve essere "installato e te lo chiederà nel momento in cui lo usi ("npm install -D sass")" -->
<style lang="scss" scoped>
.img-center {
  text-align: center;
}
img {
  width: 300px;
}
</style>
