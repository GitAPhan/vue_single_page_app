<template>
  <div id="page_header">
    <img src="http://placeskull.com/50/50/000000/1" alt="random skull logo" />
    <div id="header_links">
      <a href="#">Home</a>
      <a href="#">About Us</a>
      <a href="#">Contact Us</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "page-header",
};
</script>

<style scoped>
#page_header {
    background-color: black;
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 5fr;
}

#header_links {
    display: grid;
    grid-auto-flow: column;
    place-items: center;
}
</style>