<template>
  <Layout>
    <div class="container">

      <div class="contact-header">
        <h1 class="contact-title">Interactive Map of the cemetery</h1>
      </div>

        <div id="cemeteryMapContainer" class="map" >
          <center>
            <img src="https://mir-s3-cdn-cf.behance.net/project_modules/disp/1f430a36197347.57135ca19bbf5.gif"/>
          </center>
        </div>

      <br/>
      <br/>
      <br/>
      <br/>

      <script type="application/javascript" src="/cemLib.js" />
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
  position: absolute;
  left:5%;
  margin-bottom: 10em;
  width:90vw;
}
</style>

