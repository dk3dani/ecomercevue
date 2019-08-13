<template>

			<div id="header">
				<!-- container -->
				<div class="container">
					<!-- row -->
					

						<!-- SEARCH BAR -->
						<div class="col-md-6">
							<div class="header-search">
								<form>
									<select class="input-select">
										<option value="0">Categorias</option>
										<option value="1">Computadores</option>
										<option value="1">Cameras</option>
									</select>
									<input class="input" placeholder="O que você deseja buscar?">
									<button class="search-btn">Buscar</button>
								</form>
							</div>
						</div>
						<!-- /SEARCH BAR -->

						<!-- ACCOUNT -->
						<div class="col-md-3 clearfix">
							<div class="header-ctn">
								<!-- Wishlist -->
								<div>
									<a href="#">
										<i class="fa fa-heart-o"></i>
										<span>Sua lista</span>
										<div class="qty">{{favoritos}}</div>
									</a>
								</div>
								<!-- /Wishlist -->

								<!-- Cart -->
								<div class="dropdown">
									<a class="dropdown-toggle" data-toggle="dropdown" aria-expanded="true">
										<i class="fa fa-shopping-cart"></i>
										<span>Carrinho</span>
										<div class="qty"><p>{{carrinho}}</p></div>
									</a>
									
								</div>
								<!-- /Cart -->

								<!-- Menu Toogle -->
								<div class="menu-toggle">
									<a href="#">
										<i class="fa fa-bars"></i>
										<span>Menu</span>
									</a>
								</div>
								<!-- /Menu Toogle -->
							</div>
						</div>
						<!-- /ACCOUNT -->
					</div>
					<!-- row -->
				</div>
				<!-- container -->
	




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
 