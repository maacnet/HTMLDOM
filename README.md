# HTML DOM
Repositório sobre HTML DOM

O HTML DOM é um padrão para definir um documento HTML.

Manipular o DOM é Obter - Inserir - Alterar - Excluir 

Elementos
Eventos do HTML

Métodos são Ações e Propriedades são valores do HTML

----------------------------------------------------------------------

Html DOM pode ser acessado por JavaScript (ou outras linguagens)
No DOM todos os elementos são definidos como objetos

----------------------------------------------------------------------

document.getElementById é forma mais fácil de acessar um elemento Html
document.getElementById("demo").innerHTML = "Hello World!";

----------------------------------------------------------------------

A propriedade innerHTML pode ser usada para obter ou subtituir o conteúdo dentro
de uma tag Html

----------------------------------------------------------------------

## Encontrando os Elementos Html

O objeto "document" é literalmente toda a página html, esse objeto
pode acessar todas as tags htmls dentro da página.

document.getElementById(id) -> encontra o elemento pelo Id
document.getElementsByTagName(name) -> Encontra o elemento pela tag
document.getElementsByClassName(name) -> encontra o elemento pelo nome da classe

----------------------------------------------------------------------

## Alterando os elementos HTML

Propriedade

.innerHTML = "Novo conteúdo" -> Muda o contéudo
.attribute = "Novo Valor" -> Muda o valor da propriedade da tag
.style.property = "Novo Estilo" -> Muda o estilo da tag


Método

.setAttibute(attribute,value) = Muda o atributo e valor de uma tag HTML

----------------------------------------------------------------------
## Adicionado ou Excluíndo um Elemento

document.createElement(element)
document.removeChild(element)
document.appendChild(element)
document.replaceChild(new, old)
document.write(text)

----------------------------------------------------------------------
## Adicionar um manipulador de Evento

document.getElementById(id).onclick = function(){code}

----------------------------------------------------------------------

## Objetos pré definidos pelo DOM 1 e 3

document.anchors		        Returns all <a> elements that have a name attribute	1
document.baseURI		        Returns the absolute base URI of the document	3
document.body			        Returns the <body> element	1
document.cookie			        Returns the document's cookie	1
document.doctype		        Returns the document's doctype	3
document.documentElement	    Returns the <html> element	3
document.documentMode		    Returns the mode used by the browser	3
document.documentURI		    Returns the URI of the document	3
document.domain			        Returns the domain name of the document server	1
document.embeds			        Returns all <embed> elements	3
document.forms			        Returns all <form> elements	1
document.head			        Returns the <head> element	3
document.images			        Returns all <img> elements	1
document.implementation		    Returns the DOM implementation	3
document.inputEncoding		    Returns the document's encoding (character set)	3
document.lastModified		    Returns the date and time the document was updated	3
document.links			        Returns all <area> and <a> elements that have a href attribute	1
document.readyState		        Returns the (loading) status of the document	3
document.referrer		        Returns the URI of the referrer (the linking document)	1
document.scripts		        Returns all <script> elements	3
document.strictErrorChecking	Returns if error checking is enforced	3
document.title			        Returns the <title> element	1
document.URL			        Returns the complete URL of the document	1












































