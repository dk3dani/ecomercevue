<template>
  <div id="app">
    
    <router-view/>
  </div>
</template>
<script>
 export default {
     
             data(){
                 return{
                     produto: "Notebook ",
                    descricao: "Notebook DELL Memória: 8GB HD: 2TB SSD: 480GB - LT-P10880G-13M",                
                    qtde: 15,
					favoritos:0,
                    emEstoque: false,
                    carrinho: 0}} 
                    ,
                methods:{
                adicionarCarrinho: function(){
                    this.carrinho += 1,
					this.qtde -= 1},

					 adicionarFavoritos: function(){
						 this.favoritos =1
					 }
					
					
					}    
                    
                   



                } 
                
                   
 
                
                
 </script>
 