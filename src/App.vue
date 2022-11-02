<template>
  <div class="mt-10 text-3xl mx-auto max-w-6xl">
    <Header/>
    <div>Global MFE</div>
    <Footer/>
  </div>
</template>
<script>
import Header from "./Header.vue";
import Footer from "./Footer.vue";

export default{
  components:{
    Header,
    Footer,
  }
}
</script>