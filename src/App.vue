<template>
  <div id="app">
    <div class="container" style="width:600px">
      <div class="my-4">
        <p id="devname"><span>Amica</span></p>
        <h4>Vue.js upload Image with Preview</h4>
      </div>
      <upload-image></upload-image>
    </div>
	<footer-page></footer-page>
  </div>
</template>

<script>
import UploadImage from "./components/UploadImage";
import FooterPage from './components/Footer';

export default {
  name: "App",
  components: {
    UploadImage,
	FooterPage
  }
};
</script>
<style>
#devname span{ background-color:#000000; color:#FFFFFF; width:100px; height:100px; padding:20px 10px; border-radius:50%; font-size:15px; }
</style>
