<template>
  <div id="meet_the_developer">
    <img src="http://fakeimg.pl/150x200?text=person&font=lobster" alt="" />
    <section>
      <h3>Name of developer</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi
        quidem eos consequatur mollitia possimus ducimus adipisci, natus,
        ratione eveniet tempore reiciendis veniam debitis? Totam ut sit iusto
        consequatur sunt fugiat?
      </p>
      <h4>Title of developer</h4>
    </section>
  </div>
</template>

<script>
export default {
  name: "meet-the-developer",
};
</script>

<style scoped>
#meet_the_developer {
    display: grid;
    place-items: center;
    grid-auto-flow: column;
    column-gap: 20px;
    width: 100%;
}
section {
  display: grid;
  justify-items: start;
  align-items: center;
  
}
p {
    text-align: left;
}
</style>