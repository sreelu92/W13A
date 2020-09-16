<template>
  <div class="page-footer">
    <div></div>
    <h3>Jobs</h3>
    <h3>Support</h3>
    <h3>Terms of Serice</h3>
    <div></div>
  </div>
</template>


<script>
export default {
  name: "page-footer"
};
</script>

<style scoped>
.page-footer {
  display: grid;
  justify-items: center;
  align-items: center;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
      background-color:lightgray;

}

</style>