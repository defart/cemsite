<template>
  <Layout>
    <div class="container">

      <div class="contact-header">
        <h1 class="contact-title">Interactive Map of the cemetery</h1>
      </div>

        <div id="cemmap" class="map"> 
        </div>
    </div>
  </Layout>
</template>

<script>
export default {}
</script>

<style scoped>
.contact-header {
  padding: 2rem 0 4rem 0;
}
.contact-title {
  font-size: 4rem;
  margin: 0 0 4rem 0;
  padding: 0;
}

.map {
  width:100%;
  height: 50em;
  border: 1px solid black;
}
</style>

