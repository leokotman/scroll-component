<template>
  <section class="scroller">
    <li v-for="item in list" :key="item">
      {{ item }}
    </li>
  </section>
</template>

<script>
export default {
  props: ["list"],
};
</script>

<style scoped>
.scroller {
  background-image: url("../assets/bg-iphone.png");
  background-repeat: no-repeat;
  background-size: auto;
  font-family: Open Sans;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  letter-spacing: 0em;
  text-align: left;
  color: white;
  width: 276px;
  height: 460px;
}
</style>
