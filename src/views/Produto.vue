<template>
  <div class="produto">
    <div class="top">
      <Topheader/>
    </div>
    
    

    <div class="produto">
      <Compra/>
    </div>
    
  </div>
</template>


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
  name: "produto",
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
