<template>
    <div class="header-grid">
        <img class="images" alt="Vue logo" src="../assets/logo.png">
        <h3>About us</h3>
        <h3>Location</h3>
        <h3>Menu</h3>
    </div>

</template>

<script>

    export default {
        name: "page-header"
    };

</script>

<style scoped>
.header-grid {
    display: grid;
    justify-items: center;
    align-items: center;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    background-color:lightgray;
}
.images {
    width: 100px;
    height: 100px;
}

</style>