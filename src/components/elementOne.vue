<template>
  <div class="element-one">
    <div class="borderStyle">
      <h4>choice one</h4>
      <h4>choice two</h4>
      <h4>choice three</h4>
    </div>
  </div>
</template>

<script>
export default {
  name: "body-element",
};
</script>

<style scoped>
.element-one {
  display: grid;
  justify-items: center;
  align-items: center;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}
.borderStyle {
    border: 2px solid black;
    padding: 15px;

}
</style>