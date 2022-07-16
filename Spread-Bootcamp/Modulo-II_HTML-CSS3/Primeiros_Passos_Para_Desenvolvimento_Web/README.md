# Primeiros Passos Para Desenvolvimento Web
## Aula Prática

#### Código-fonte de página simples contendo trechos da obra taoísta "Dao De Jing", escrita pelo filósofo LaoZi [(*index.html*)](https://github.com/FawkesC05/dio-notes/tree/main/Spread-Bootcamp/Modulo-II_HTML-CSS3/Primeiros_Passos_Para_Desenvolvimento_Web/Aula_Pratica/index.html):

``` <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Trechos de "Dao De Jing - O Livro do Caminho e da Virtude"</title>
  <link rel="stylesheet" href="//code.jquery.com/ui/1.13.2/themes/base/jquery-ui.css">
  <script src="https://code.jquery.com/jquery-3.6.0.js"></script>
  <script src="https://code.jquery.com/ui/1.13.2/jquery-ui.js"></script>
  <script>
  $( function() {
    $( "#accordion" ).accordion({
      heightStyle: "content"
    });
  } );
  </script>
</head>
<body>
<h1 style="text-align:center;">Trechos de "Dao De Jing - O Livro do Caminho e da Virtude"</h1>
<div id="accordion">
  <h3>Capítulo 1</h3>
  <div>
  	<blockquote cite="https://pt.wikipedia.org/wiki/Tao_Te_Ching">
  	<i>
    <p>
    O caminho que pode ser ensinado
	</br>
    Não é o caminho eterno
	</br>
    O nome que pode ser falado
	</br>
    Não é o nome eterno
	</br>
    O inominável é o eterno real
	</br>
    Nomear é a origem de todas as coisas separadas.
	</br>
    Livre do desejo você vê o mistério
	</br>
    Preso no desejo você vê apenas as manifestações
	</br>
    No entanto, mistério e manifestações surgem da mesma fonte
	</br>
    Essa fonte é chamada escuridão
	</br>
    Escuridão dentro da escuridão
	</br>
    O portal para todo o entendimento.
	</p>
	</i>
	</blockquote>
  </div>
  <h3>Capítulo 11</h3>
  <div>
  	<blockquote cite="https://pt.wikipedia.org/wiki/Tao_Te_Ching">
  	<i>
    <p>
    Trinta raios convergem para o meio de uma roda,
	</br>
    Mas é o buraco em que vai entrar o eixo que a torna útil.
	</br>
    Molda-se o barro para fazer um vaso;
	</br>
    É o espaço dentro dele que o torna útil.
	</br>
    Fazem-se portas e janelas para um quarto;
	</br>
    São os buracos que o tornam útil.
	</br>
    Por isso, a vantagem do que está lá
	</br>
    Assenta exclusivamente
	</br>
    Na utilidade do que lá não está.
	</p>
	</i>
	</blockquote>
  </div>
  <h3>Capítulo 41</h3>
  <div>
  	<blockquote cite="https://pt.wikipedia.org/wiki/Tao_Te_Ching">
  	<i>
    <p>
    Quando um estudioso mais sábio ouve falar no Tao,
	</br>
    Abraça-o com zelo.
	</br>
    Quando um estudioso médio ouve falar no Tao,
	</br>
    Pensa nele de vez em quando.
	</br>
    Quando um estudioso inferior ouve falar no Tao,
	</br>
    Ri-se às gargalhadas.
	</br>
    Se ele não risse,
	</br>
    O Tao não seria o Tao (o caminho).
    </p>
    </i>
    </blockquote>
  </div>
  <h3>Capítulo 4</h3>
  <div>
  	<blockquote cite="https://pt.wikipedia.org/wiki/Tao_Te_Ching">
  	<i>
    <p>
    O Tao é como o espaço vazio dentro de um vaso;
	</br>
    Mas, por mais que o enchamos, nunca ficará cheio.
	</br>
    É incomensurável, como se fosse o Antepassado de todas as coisas.
    </p>
    </i>
    </blockquote>
  </div>
</div>

</br></br>

<h5><blockquote cite="https://pt.wikipedia.org/wiki/Tao_Te_Ching">Fonte: https://pt.wikipedia.org/wiki/Tao_Te_Ching</blockquote></h5>
 
</body>
</html>