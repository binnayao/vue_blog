<template>
  <div class="box">
    <Nav />
    <div class="top row subCenter mainCenter">
      <div class="title">Biu, Biu, Biu ~</div>
    </div>
    <Content />
    <Footer />
  </div>
</template>

<script>
import Nav from "./nav";
import Content from "./content";
import Footer from "./footer";
export default {
  name: "Box",
  data() {
    return {};
  },
  components: {
    Nav,
    Content,
    Footer
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.box {
  height: 100%;
}
.top {
  background-image: url("../../assets/about-bg.jpg");
  height: 400px;
  width: 100%;
  background-size: cover;
  background-position: center;
}
.title {
  font-size: 60px;
  color: #fff;
  font-weight: bold;
  letter-spacing: 1px;
}
</style>
