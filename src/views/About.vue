<template>
  <div class="about">
    <div class="top">
      <Topheader/>
    </div>
    <div class="nav">
      <Navbar/>
    </div>
    <h1>Trabalho sobre os E-commerces</h1>
    <center><iframe src="https://drive.google.com/file/d/1tqgxGfDuuBIzPmQZ8QSvCH4fXeLI7uvb/preview" width="1024" height="800"></iframe></center>
   
  </div>
</template>
<style scoped>
h1{

text-align: center;

}
</style>

<script>
// @ is an alias to /src
import Topheader from "@/components/Topheader.vue";
import Mainheader from "@/components/Mainheader.vue";
import Navbar from "@/components/Navbar.vue";
import Section from "@/components/Section.vue";
import News from "@/components/News.vue";
import Conteudo from "@/components/Conteudo.vue";
import Compra from "@/components/Compra.vue";
export default {
  name: "about",
  components: {
    Topheader,
    Mainheader,
    Navbar,
    Section,
    News,
    Conteudo,
    Compra
  }
};
</script>
