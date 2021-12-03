<template>
  <div id="page_footer">
      <a href="#">facebook</a>
      <a href="#">linkedin</a>
      <a href="#">instagram</a>
  </div>
</template>

<script>
export default {
  name: "page-footer",
};
</script>

<style scoped>
#page_footer {
    background-color: rgba(0, 0, 0, 0.473);
    width: 100%;
    display: grid;
    grid-auto-flow: column;
    place-items: center;
}
</style>