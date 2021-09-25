# Desafio Individual – Site de Cadastro Pessoal

## Autoria

- **Nome:** Edivaldo Aparecido Dias
- **Idade:** 41 Anos
- **Tipo de deficiência:** Nervo óptico atrofiado no olho direito.
- **CID:** H54.5

## Descrição

### HTML

No arquivo com nome de `index` em uma extensão de `.html`, começa com uma declaração `<!DOCTYPE>`, que informa o tipo de documento para os navegadores, `html` contendo o atributo `lang` que define uma língua e logo um elemento `head`, que é um container para metadados (`<meta>`) e é colocado entre os elementos `<html>` e `<body>`.

Dentro do `head`, temos metadados (`meta`), que são dados sobre o documento HTML e não são exibidos, podem fornecer a codificação de caracteres, o cabeçalho HTTP para o valor do conteúdo, definir a visualizacão para funcionar em todos os dispositivos. Finalmente, temos um elemento `title`, que define um título para o documento HTML.

Depois de `head` fechado, temos um elemento `body` que define o corpo do documento e pode conter todo o conteúdo de um documento HTML, como títulos, parágrafos, imagens, *hyperlinks*, tabelas, listas, etc.

A etiqueta `<div class="container">` é um bloqueio com um atributo `class` que define o estilo. Significa centralizar e limitar a largura máxima.

Dentro desse bloqueio, temos um título de primeiro cabeçalho (`<h1>`), um parágrafo (`<p>`) e um formulário (`<form`). Num parágrafo com o elemento `<p>`, temos o elemento `<span class="asterico">*</span>`, significando que o asterico é pintado em cor vermelha. 

O elemento `<form>` é usado para criar um formulário HTML para entrada do usuário, e contém atributos `action` (encaminhamento da página externa ao enviar) e `methpd="get"` (especifica o método HTTP a ser usado ao enviar dados do formulário).

Dentro desse formulário, agrupamos os bloqueios de campos de entrada com rótulos para a mesma linha, usando a grade (`grid`) na propriedade `display`. 

Temos rótulos (`label`), campos de entrada (`input`), lista suspensa de opções (`select`) e um botão (`<input type="submit">`). 

Os campos de entrada podem conter os atributos `type` (tipo de campo de entrada), `name` (nome do campo), `id` (identificador do campo de entrada para vincular-se ao rótulo (`label`) que contém um atributo `for`), `pattern` (uma expressão regular que valida a entrada do campo), `placeholder` (um valor da pequena dica) e `aria-rqeuired` (uma das regras da WCAG, semelhante ao `required`, designado para pessoas com deficiência visual e leitores de tela).

No fim, temos um botão definido como uma submissão contendo o atributo `value`, que é um valor, e o evento de JavaScript `onclick` que executa uma função em JavaScript quando o botão é clicado.

Depois, o elemento `<script>` é usado para incorporar um *script* do lado do cliente (JavaScript) ou anexa um arquivo externo em JavaScript.

# Referências

- [Expressão regular de RG](https://pt.stackoverflow.com/questions/22431/express%C3%A3o-regular-para-rg)
- [EXpressão regular de CPF](https://pt.stackoverflow.com/questions/11045/express%C3%A3o-regular-para-validar-um-campo-que-aceita-cpf-ou-cnpj)
- [CSS Grid Layout e Flexbox - Quando Utilizar](https://www.youtube.com/watch?v=x-4z_u8LcGc)
- [Usando o atributo `aria-required`](https://developer.mozilla.org/pt-BR/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-required_attribute)

