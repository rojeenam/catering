<template>
  <v-carousel>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
      cycle
    ></v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          src: require("../assets/img1.jpg")
        },
        {
          src: require("../assets/img2.jpg")
        },
        {
          src: require("../assets/img3.jpg")
        }
      ]
    };
  }
};
</script>