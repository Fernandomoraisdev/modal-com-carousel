<!doctype html>
<html lang="pt-BR">

<head>
	<title>Trabalho PCA AP3</title>
	<!-- Required meta tags -->
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link rel="stylesheet" href="./css/estiloLayout.css">

	<!-- Bootstrap CSS -->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
		integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
</head>

<body>


	<div class="container">
		<header>
			<figure class="logotipo">
				<img class="logo-unigranrio" src="img/logo.jpg" alt="banner">
			</figure>
			<nav class="navtopo">
				<a href="index.html">Home</a>
				<a href="#História">História</a>
				<a href="#Fotos">Fotos</a>
				<a href="#contato">Contato</a>
				<a href="#mymodelcadastro" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModalcadastro">Cadastro</a>
				<a href="#mymodal" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">Login</a>

				<div class="modal fade" id="myModal" tabindex="-1" role="dialog">
					<div class="modal-dialog" role="document">
						<div class="modal-content">
							<div class="modal-header">
								<h5 class="modal-title">Login</h5>
								<button type="button" class="close" data-dismiss="modal">
									<span>&times;</span>
								</button>
							</div>
							<div class="modal-body">
								 <form >
								  <div class="form-group">
									<label for="recipient-name"class="control-label" >Login:</label>
									<input type="text" class="form-control" id="recipient-name" name="login" placeholder="Login">
								  </div>
								  <div class="form-group">
									<label for="message-text" class="control-label">Senha:</label>
									<input type="password" class="form-control" id="recipient-name" name="senha" placeholder="Senha">
								  </div>
								</form>  
							</div>
							<div class="modal-footer">
								<button type="button" class="btn btn-danger" data-dismiss="modal">Fechar</button>
								  <button type="button" class="btn btn-primary">Logar</button>
							</div>
						</div>
					</div>
				</div>

				<div class="modal fade" id="myModalcadastro" tabindex="-1" role="dialog">
					<div class="modal-dialog" role="document">
						<div class="modal-content">
							<div class="modal-header">
								<h5 class="modal-title">Cadastro</h5>
								<button type="button" class="close" data-dismiss="modal">
									<span>&times;</span>
								</button>
							</div>
							<div class="modal-body">
								 <form >
								  <div class="form-group">
									<label for="recipient-name"class="control-label" >Nome:</label>
									<input type="text" class="form-control" id="recipient-name" name="Nome" placeholder="Nome">
								  </div>
								  <div class="form-group">
									<label for="message-text" class="control-label">E-mail:</label>
									<input type="password" class="form-control" id="recipient-name" name="email" placeholder="E-mail">
								  </div>
								  <div class="form-group">
									<label for="message-text" class="control-label">Telefone:</label>
									<input type="password" class="form-control" id="recipient-name" name="telefone" placeholder="Telefone">
								  </div>
								  <div class="form-group">
									<label for="message-text" class="control-label">Senha:</label>
									<input type="password" class="form-control" id="recipient-name" name="senha" placeholder="Senha">
								  </div>
								  <div class="form-group">
									<label for="message-text" class="control-label">Confime sua Senha:</label>
									<input type="password" class="form-control" id="recipient-name" name="senha" placeholder="Confirme sua senha">
								  </div>
								</form>  
							</div>
							<div class="modal-footer">
								<button type="button" class="btn btn-danger" data-dismiss="modal">Fechar</button>
								  <button type="button" class="btn btn-primary">Confirmar</button>
							</div>
						</div>
					</div>
				</div>
			</nav>
		</header>

		<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
			<div class="carousel-inner">
				<div class="carousel-item active">
					<img class="d-block w-100" src="./img/img1.jpg" alt="First slide">
				</div>
				...
				<div class="carousel-item">
					<img class="d-block w-100" src="./img/img2.jpg" alt="Second slide">
				</div>
				...
				<div class="carousel-item">
					<img class="d-block w-100" src="./img/img3.jpg" alt="Third slide">
				</div>
				...
				<div class="carousel-item">
					<img class="d-block w-100" src="./img/img4.jpg" alt="Third slide">
				</div>
				...
				<div class="carousel-item">
					<img class="d-block w-100" src="./img/img5.jpg" alt="Third slide">
				</div>
				...
				<div class="carousel-item">
					<img class="d-block w-100" src="./img/img6.jpg" alt="Third slide">
				</div>
			</div>
			<a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
				<span class="carousel-control-prev-icon" aria-hidden="true"></span>
				<span class="sr-only">Previous</span>
			</a>
			<a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
				<span class="carousel-control-next-icon" aria-hidden="true"></span>
				<span class="sr-only">Next</span>
			</a>
		</div>
	
		<div class="foto">
			<div class="container1">
				<img  src="img/img7.jfif" class="box box01">
				<div class="colorbox1">
					<p>Lorem ipsum dolor sit amet 
					consectetur adipiscing elit pellentesque maximus 
					euismod fusce cursus vitae vel urna, nascetur 
					eget lobortis mollis dis tortor habitant fames 
					dui dictum massa rhoncus curae fermentum.</p>
				</div>
			</div>

			<div class="container2">
				<img src="img/img8.jfif" class="box box02">
				<div class="colorbox2">
					<p>Lorem ipsum dolor sit amet 
						consectetur adipiscing elit pellentesque maximus 
						euismod fusce cursus vitae vel urna, nascetur 
						eget lobortis mollis dis tortor habitant fames 
						dui dictum massa rhoncus curae fermentum.</p>
				</div>
			</div>

			<div class="container3">
					<img src="img/img9.jfif" class="box box03">
		
				<div class="colorbox3">
					<p>Lorem ipsum dolor sit amet 
						consectetur adipiscing elit pellentesque maximus 
						euismod fusce cursus vitae vel urna, nascetur 
						eget lobortis mollis dis tortor habitant fames 
						dui dictum massa rhoncus curae fermentum.
					</p>
				</div>
			</div>
		</div>

		<section id="História">
			<h1>História</h1>
			<p>Lorem ipsum dolor sit amet consectetur adipiscing elit 
			pellentesque maximus euismod fusce cursus vitae vel urna, 
			nascetur eget lobortis mollis dis tortor habitant fames dui 
			dictum massa rhoncus curae fermentum. Sodales lobortis class 
			volutpat libero egestas mus, commodo phasellus consectetur 
			tempus suscipit elementum, orci quisque vulputate nostra fringilla. 
			Ad enim mauris dolor quis convallis tincidunt hac, aenean eget 
			tempus ultricies hendrerit potenti nascetur, turpis lacus magna 
			tempor facilisis cras. Imperdiet ligula aliquet donec urna mollis 
			ipsum enim vivamus himenaeos, tincidunt dignissim cubilia platea 
			aenean odio integer maecenas leo, tortor ad mi facilisi neque 
			fringilla nisl at. Ultrices tortor nisi nec vitae lectus torquent 
			nam erat diam, sed litora at ipsum lacinia non molestie arcu nullam, 
			faucibus aliquet suscipit dignissim dictumst morbi habitasse elit.</p>
		</section>

		<footer class="rodape">Modificado por Fernando dos Santos Morais</footer>
		
		<section id="contato" class="contato">
			<p>Para contato Tel: (00)00000-0000           E-mail:xxxxxxxx@xxxxxxx.xxx</p>
		</section>
	</div>

	<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
		integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
		crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
		integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
		crossorigin="anonymous"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
		integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
		crossorigin="anonymous"></script>
</body>

</html>
