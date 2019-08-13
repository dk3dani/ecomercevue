<template>
  <div class="home">
    
<div class="top">
      <Topheader/>
    </div>
    <div class="mainheader">
      <Mainheader/>
    </div>
    <div class="Nav">
      <Navbar/>
    </div>

    <div class="New">
      <conteudo/>
      <News/>
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
export default {
  name: 'home',
  components: {
    Topheader,
    Mainheader,
    Navbar,
    Section,
    News,
    Conteudo
  }
}
</script>
