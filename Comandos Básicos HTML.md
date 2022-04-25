# Comandos Básicos HTML

## Tags importantes de um documento HTML

Como dito na [introdução](https://portaldesenvolvedor.com/html/introducao-ao-html/), todos os documentos HTML precisam começar com um tipo de declaração. Elas servem para informar ao navegador como interpretar a exibição de seu conteúdo.

### Declaração de início e fim de documento

Um documento HTML começa com **<html> e termina com </html>.** A parte visível do HTML ficará entre as marcações <body> e </body>.

A primeira secção contém geralmente as tags <title> e </title>. A segunda seção contém informações que formatam o texto da página, imagens e links.



Um arquivo html, normalmente estará associado a uma extensão .html ou htm. Por exemplo: pagina.html ou galeria.htm.

Veja o exemplo abaixo:

**<!DOCTYPE html>**

<**html**>

<**body**>

<**h1**>Primeiro título em HTML</**h1**>

<p>Meu primeiro parágrafo feito em HTML.</p>

</**body**>

</**html**>

### Títulos

Títulos são importantes em qualquer documento.

Além de ser mais compreensível para um usuário fazer a leitura do seu site, sistemas de busca utilizam para verificar a relevância do seu conteúdo com a busca dos usuários.

Os títulos em HTML são definidos de <h1> até <h6>.

<**h1**>Este é o primeiro título</**h1**>

<**h2**>Este é o subtítulo 2</**h2**>

<**h3**>Este é o subtítulo 3</**h3**> 

<**h4**>Este é o subtítulo 4</**h4**> 

<**h5**>Este é o subtítulo 5</**h5**> 

<**h6**>Este é o subtítulo 6</**h6**>

### Parágrafos

Os parágrafos em HTML são definidos através da marcação <p>.

<p>Este é um parágrafo em HTML.</p>

### Texto em negrito

Você pode facilmente adicionar negrito em seus textos, adicionando a tag <strong>. Veja o exemplo abaixo:

<**strong**>Texto em negrito</**strong**>

### Links

Links (ou texto âncora) são importantes para ligar conteúdos em documentos HTML. Para criar links em HTML, basta utilizar a tag **<a>**.

Note que é necessário utilizar o atributo href, que mostra para onde o navegador deve direcionar o usuário caso o link seja clicado.

<a href="https://portaldesenvolvedor.com">Portal Desenvolvedor</a>

Além disso, você tem alguns atributos que podem ser utilizados dentro a tag <a>:

- href=”endereço” Localização do endereço que será direcionado.
- name=”??” Nome do autor
- target=”?” para onde o link será aberto: _self, _blank, _top, _parent.
- href=”url#bookmark” Adiciona o site aos favoritos.
- href=”mailto:email” É utilizado para criar um link para o e-mail. Dependerá do cliente de e-mail instalado no dispositivo do usuário. No entanto, não é uma boa prática. O ideal neste caso é utilizar um [formulário de contato](https://portaldesenvolvedor.com/blog/como-criar-um-formulario-de-contato-em-html-e-php/).

### Listas

Você pode criar listas em HTML facilmente utilizando as tags.

- <ol> … </ol> Lista ordenada
- <ul> … </ul> Lista sem ordem
- <li> … </li> Itens de uma lista. Podem ser utilizado tanto com as tags <ol> quanto <ul>
- <ol type=”?”> Define o tipo de ordenação: A, a, I, i, 1
- <ol start=”??”> Define o valor de início da lista.
- <ul type=”?”> Define o tipo de lista não-ordenada: disc, circle, square
- <li value=”??”> Define o valor do item
- <li type=”??”> Define o tipo do item
- <dl> … </dl> Lista de conceitos
- <dt> … </dt> Termo ou frase
- <dd> … </dd> Definição detalhada sobre o tiem

### Imagens

Imagens são importantes para um conteúdo rico e ilustrado. Nós utilizamos a tag <img> para esta finalidade. A propriedade src são atributos que nós podemos utilizar para configurar qual imagem será utilizada.

<img src="portaldesenvolvedor.jpg" />

Note que a tag encerra com />. Isto foi uma inovação no XHTML, indica que a marcação é uma instrução completa e não precisa ser encerrada. Nós falaremos mais para frente nos próximos artigos.

## Formatação de corpo da página

A tag body é responsável por controlar a aparência básica da página, como cor ou imagem de fundo, cor do texto, margem e muito mais.

Exemplo:

<**body** bgcolor="#FFFFFF">

Além disso, temos os seguintes atributos do comando Body:

- background=”url” – Endereço da imagem de fundo
- bgcolor=”#” – Cor de fundo
- text=”#” – Cor do texto
- link=”#” – Cor do Link
- vlink=”#” Cor do link que foi visitado pelo usuário no mesmo navegador
- alink=”#” Cor do link ativo

Esses atributos podem também ser controlados pelo CSS. Além disso, é uma boa prática de desenvolvimento Web.

## Caracteres especiais no HTML

Você também pode utilizar caracteres especiais em seus sites, e desta forma, não serem confundidos com outras tags HTML. Os comandos HTML abaixo podem ser utilizados livremente, sem a necessidade dos sinais < e >.

- &lt; < – Menor que;
- &gt; > – Maior que;
- &amp; & – E comercial;
- &quot; ” – Sinal de citação;
- &copy; © – Copyright;
- &trade; ™ – Trademark;
- &nbsp; – Espaço;

## Conclusão

Como você sabe, HTML é essencial por sua aplicação em diversos tipos de projeto na Internet.

Conhecer comandos HTML também ajuda iniciantes a entenderem mais o mundo da programação. Normalmente, o HTML é o um primeiro grande passo no desenvolvimento de software para Internet.