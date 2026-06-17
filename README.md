# sustentabilidade-em-ac-o
Site educativo sobre sustentabilidade feito com HTML e CSS.
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sustentabilidade - Planeta Verde</title>
<link rel="stylesheet" href="estilo.css">
</head>

<body>

<header>
<h1>🌱 Planeta Sustentável</h1>
<p>Construindo um futuro melhor para todos</p>
</header>

<nav>
<a href="#sobre">Sobre</a>
<a href="#problemas">Problemas</a>
<a href="#solucoes">Soluções</a>
<a href="#reciclagem">Reciclagem</a>
<a href="#energia">Energia Limpa</a>
<a href="#acoes">Ações</a>
</nav>

<section id="sobre">
<h2>🌍 O que é Sustentabilidade?</h2>
<p>
Sustentabilidade é o uso consciente dos recursos naturais, garantindo que as próximas gerações também possam utilizá-los.
</p>
</section>

<section id="problemas">
<h2>⚠️ Problemas Ambientais</h2>
<ul>
<li>Desmatamento</li>
<li>Poluição do ar</li>
<li>Poluição da água</li>
<li>Aquecimento global</li>
<li>Extinção de espécies</li>
</ul>
</section>

<section id="solucoes">
<h2>🌿 Soluções Sustentáveis</h2>
<ul>
<li>Reduzir o uso de plástico</li>
<li>Economizar água</li>
<li>Reflorestar áreas</li>
<li>Consumo consciente</li>
<li>Educação ambiental</li>
</ul>
</section>

<section id="reciclagem">
<h2>♻️ Reciclagem</h2>
<p>A reciclagem ajuda a reduzir o lixo e reaproveitar materiais.</p>

<div class="cartoes">
<div class="cartao">
<h3>Plástico</h3>
<p>Pode virar novos produtos.</p>
</div>

<div class="cartao">
<h3>Papel</h3>
<p>Transforma-se em embalagens e cadernos.</p>
</div>

<div class="cartao">
<h3>Vidro</h3>
<p>Pode ser reciclado infinitamente.</p>
</div>
</div>
</section>

<section id="energia">
<h2>⚡ Energia Limpa</h2>
<ul>
<li>Energia solar</li>
<li>Energia eólica</li>
<li>Energia hidrelétrica</li>
<li>Biomassa</li>
</ul>
</section>

<section id="acoes">
<h2>🌎 O que você pode fazer?</h2>
<ul>
<li>Economizar água</li>
<li>Evitar desperdício</li>
<li>Usar bicicleta ou transporte público</li>
<li>Reciclar lixo</li>
<li>Plantar árvores</li>
</ul>
</section>

<footer>
<p>Site educativo sobre sustentabilidade</p>
</footer>

</body>
</html>
body {
margin: 0;
font-family: Arial, sans-serif;
background-color: #f0f7f2;
color: #2e3d2f;
}

header {
background: linear-gradient(90deg, #2e7d32, #66bb6a);
color: white;
text-align: center;
padding: 40px;
}

header h1 {
margin: 0;
}

nav {
background-color: #1b5e20;
display: flex;
justify-content: center;
flex-wrap: wrap;
}

nav a {
color: white;
padding: 14px 20px;
text-decoration: none;
}

nav a:hover {
background-color: #43a047;
}

section {
padding: 40px 20px;
max-width: 1000px;
margin: auto;
}

h2 {
color: #2e7d32;
}

ul {
line-height: 1.8;
}

.cartoes {
display: flex;
gap: 20px;
flex-wrap: wrap;
}

.cartao {
background: white;
padding: 20px;
border-radius: 10px;
flex: 1;
min-width: 200px;
box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

footer {
text-align: center;
padding: 20px;
background-color: #1b5e20;
color: white;
}
