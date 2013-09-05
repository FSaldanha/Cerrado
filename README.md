(English version coming soon!)

Cerrado
=======

Cerrado é um conceito de extensão para HTML com o intuito de agilizar o desenvolvimento front-end, automatizando certas tarefas e reduzindo a quantidade de código a ser escrito.

Exemplo
-------

Entrada:

	title {
		Cerrado
	}
	header {
		h1 {
			Olá mundo!
		}
		p (class: “texto”) {
			Você pode inserir qualquer elemento HTML com Cerrado e definir atributos normalmente.
		}
	}

Saída:

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Cerrado</title>
</head>
<body>
	<header>
		<h1>Olá mundo!</h1>
		<p class="texto">Você pode inserir qualquer elemento HTML com Cerrado e definir atributos normalmente.</p>
	</header>
</body>
</html>
```
	
Características
---------------

### Notação própria

Ao invés de tags, Cerrado utiliza blocos formados por chaves para compor os elementos HTML. Os atributos são passados individualmente ou no formato `chave: “valor”`, separados por vírgula e inseridos entre parênteses.

	elemento (atributo, atributo: “valor”) {
		//conteúdo
	}

### Integração com outras linguagens

Um código em Cerrado pode ser compilado normalmente com trechos de códigos em outras linguagens server-side, CSS e Javascript.

	style {
		//código CSS
	}
	script {
		//código Javascript
	}
	<?php
		//código server-side
	?>

### Validação integrada

Ao compilar seu código, Cerrado pode validá-lo automaticamente de acordo com as recomendações da W3C, registrando os erros em log ou diretamente no arquivo compilado.

### Organização do código

Cerrado pode ordenar os elementos HTML em uma ordem específica para otimizar a performance do código. Por exemplo, colocando as folhas de estilo dentro de `<head>` e os scripts imediatamente antes de `</body>`.

### Templates

Por padrão, Cerrado adiciona automaticamente certos trechos de código ao arquivo compilado, como a declaração `DOCTYPE` e as tags `<html>`, `<head>` e `<body>`. Você pode alterar o template padrão ou desativar completamente essa função.

Compilador
----------

Em breve!

Documentação
------------

Em breve!

Por que Cerrado?
----------------

O Cerrado é a segunda maior formação vegetal da América do Sul, ocupa um quarto do território brasileiro e é reconhecido como a região com savanas mais rica em vida no planeta. Porém, já perdeu metade de sua vegetação original. Segundo a Conservation International, o Cerrado é o bioma mais ameaçado do país, ao lado da Mata Atlântica.

Saiba mais: http://www.wwf.org.br/natureza_brasileira/areas_prioritarias/cerrado/

Conheça o trabalho da OPA, organização que atua na área do Cerrado: http://www.opa.org.br/

Licença
-------

(C) 2013 Felipe Saldanha. Todos os direitos reservados.

Você está autorizado a utilizar esse software para fins comerciais e não-comerciais, desde que mantenha os créditos no software derivado.