<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<title>Sobre a Barbearia Alura</title>
		<link rel="stylesheet" href="style.css">
	</head>

	<body>
		<header>
			<h1 class="titulo-principal"> Sobre a Barbearia Alura</h1>
		</header>
		<img id="banner" src="banner.jpg">
		<div class="principal">
			<h2 class="titulo-centralizado">Sobre a Barbearia Alura</h2>
	 
			<p> Localizada no coração da cidade a <strong> Barbearia Alura</strong> traz para o mercado oque há de melhor para o seu cabelo e barba. Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia </p>
			<p id="missao"><em>O objetivo de Morgan, que trabalhava na ACM de Holyoke no Massachusetts: <strong>era criar um esporte de equipes sem contato físico entre os adversários de modo a minimizar os riscos de lesão.</strong>.</em></p>

			<p>Nossa missão é:"Proporcionar auto-estima e qualidade de vida aos cliente".</p>
		</div>

		<div class="Benefícios">
			<h3 class="titulo-centralizado">Benefícios</h3>

			<ul>
				<li class="itens">Atendimento aos Clientes.</li>
				<li class="itens">Espaço diferenciado.</li>
				<li class="itens">Localização.</li>
				<li class="itens">Profissionais qualificados.</li>
			</ul>

			<img src="benefícios.jpg" class="imagembeneficios">
		</div>
	</body>
</html>




#banner {
	width:100%;
}

.principal{
	background: #CCCCCC;
	padding: 30px;
}

.titulo-principal {
	padding-left: 20px;
}

.titulo-centralizado {
	text-align: center
}

p {
	text-align: center;
}

#missao {
	font-size: 20px
}

em strong {
	color: #FF0000;
}

.itens {
	font-style: italic
}

.beneficios {
	background: #FFFFFF;
	padding: 20px;
}

ul {
	display: inline-block;
	vertical-align: top;
	width: 20%;
	margin-right: 15%;
}

.imagembeneficios {
	width: 50%;
}
