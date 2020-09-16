<template>
  <div class="body-grid">
    <body-element></body-element>
    <body-elementtwo></body-elementtwo>
    <body-elementthree></body-elementthree>

  </div>
</template>


<script>
import BodyElement from "./elementOne.vue";
import BodyElementtwo from "./elementTwo.vue";
import BodyElementthree from "./elementThree.vue";



export default {
  name: "page-body",
  components: {
    BodyElement,
    BodyElementtwo,
    BodyElementthree

  
  }
 
  
};
</script>


<style scoped>
.body-grid {
  display: grid;
  justify-items: center;
  align-items: center;
  column-gap: 5px;
  grid-template-columns: 1fr 3fr 3fr 1fr ;
  margin-top: 10vh;
}
</style>