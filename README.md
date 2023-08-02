 # Resumo-de-estudo

## 1- Descobrindo sobre a carreira front end e back end. 

## 2-  Aprenda a construir seu primeiro documento html: Títulos, parágrafos, imagens e links. 
      
      (Explicação e  Projeto: Parque estadual  e Barbearia)

## 3- Aprenda a construir sua primeira  pagina da web estilizada:  title, meta tag description, meta tag charset, meta tag Robots, viewport, adicionando estilos css.

### O que é meta description?

   A meta description é um conteúdo exibido na página de resultados de um buscador com um resumo do que vai ser encontrado em 
   uma página.Sempre que você realiza uma busca, os sites são listados com seus títulos, endereços e essa pequena descrição ou             apresentação de um site ou blog, por exemplo.

### O que é o meta charset no HTML?

  A meta charset=”utf-8” é uma metatag responsável por chavear qual tabela de caractéres a página está utilizando. A Web é acessada por pessoas do mundo inteiro. Ter um sistema ou um site que limite o acesso e pessoas de outros países é algo que vai contra a tradição e os ideais da internet. Por isso, foi criado uma tabela que suprisse essas necessidades, essa tabela se chama Unicode. A tabela Unicode suporta algo em torno de um milhão de caracteres.

### Meta tag robots:

  noindex: Não liste essa página nos resultados da busca.
  nofollow: Não siga os links dessa página.
       
      ( Projeto: Livro - Utilização de Css e html básico)

## 4-  Avance  na construção de paginas da web estilizadas: lista ordenadas, lista não ordenada, lista de definição, setores tag e classe, reaproveitando classes, agrupando setores, descendência de elementos.

### Listas Ordenadas:

   As listas ordenadas são usadas para apresentar itens em uma sequência específica.
   Os itens são marcados com números ou letras, indicando a ordem em que devem ser exibidos.
    Para criar uma lista ordenada, você usa a tag ol (ordered list) e envolve cada item da lista com a tag li (list item).
    
### Exemplo de código:

<ol>
  <li>Item</li>
  <li>Item</li>
  <li>Item</li>
</ol>

### Listas Não Ordenadas:

   As listas não ordenadas são usadas para apresentar itens em uma ordem não específica.
   Os itens são marcados com marcadores, geralmente pontos ou círculos, sem indicar uma sequência definida.
   Para criar uma lista não ordenada, você usa a tag <ul> (unordered list) e envolve cada item da lista com a tag <li> (list item).
    
### Exemplo de código:

 <ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

### Uma lista de definição no HTML
   
   é uma forma de apresentar termos e suas respectivas definições em um formato organizado. É como criar um pequeno dicionário ou glossário na sua página web. A estrutura básica da lista de definição consiste em dois elementos principais:
   Termos: Os termos são as palavras ou frases que você deseja definir. Eles são colocados dentro da tag <dt> (definition term).
   Definições: As definições são as explicações ou descrições dos termos. Elas são colocadas dentro da tag <dd> (definition description).

### Aqui está um exemplo simples:

<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language. É a linguagem de marcação utilizada para criar páginas web.</dd>
  
  <dt>CSS</dt>
  <dd>Cascading Style Sheets. É uma linguagem de estilo utilizada para definir a aparência das páginas web.</dd>
  
  <dt>JavaScript</dt>
  <dd>Uma linguagem de programação utilizada para tornar as páginas web interativas e dinâmicas.</dd>
</dl>

   A lista de definição é uma maneira eficiente de organizar informações e fornecer explicações claras sobre termos ou conceitos importantes em suas páginas da web.
   É útil em situações em que você deseja apresentar um vocabulário específico, um glossário técnico ou qualquer tipo de lista com termos e suas definições associadas.

      (html lista)
      (Projeto: Imobiliária e padaria)

## 5-  Aprenda a construir um website com imagens de fundo e efeitos de fundo: 

   (background image e color, valores relativos, definindo o tamanho dos elementos, overflow, exibindo e ocultando elementos, box-sizing, box-shadow, elementos fixos na tela, position absolute, position relative.)
   (Projeto: Superman, Carros, pedidos de pizza e cafeteria)

## 6 - Table: elemento HTML usado para criar uma tabela. Pode conter elementos como thead, tbody, tfoot e caption:

  #### tr: elemento HTML usado para definir uma linha em uma tabela. Deve estar dentro de um elemento table e pode conter elementos como th e td.

 #### td:
 elemento HTML usado para criar uma célula de uma tabela. Deve estar dentro de um elemento tr e pode conter dados de texto, imagens, links ou outros elementos.

 #### th:
 elemento HTML usado para criar uma célula de cabeçalho de uma tabela. Deve estar dentro de um elemento tr e geralmente contém dados de texto ou títulos.

 #### thead:
 elemento HTML usado para agrupar o cabeçalho de uma tabela. Deve estar dentro de um elemento table e normalmente contém elementos th.

 #### tbody: 
 elemento HTML usado para agrupar o corpo principal de uma tabela. Deve estar dentro de um elemento table e normalmente contém elementos tr.

 #### tfoot: 
 elemento HTML usado para agrupar o rodapé de uma tabela. Deve estar dentro de um elemento table e normalmente contém elementos tr.

 #### caption:
 elemento HTML usado para adicionar uma legenda ou título a uma tabela. Deve estar dentro de um elemento table e geralmente contém texto descritivo.

### 7 - Aprenda a construir um website com display flexível e navegação em múltiplas páginas


  ### Flexbox 
   
   é um modelo de layout em CSS que permite organizar elementos de forma flexível dentro de um contêiner, ajustando-os dinamicamente para diferentes tamanhos de tela e dispositivos. É uma abordagem bidimensional que opera em um eixo principal (horizontal ou vertical) e um eixo transversal.

  ###Display flex
  
   é uma propriedade CSS usada para criar um contêiner flex. Quando aplicada a um elemento pai (contêiner), transforma-o em um flex container, permitindo que seus filhos (itens flexíveis) sejam organizados usando as propriedades do flexbox. 

 ###   Os principais tipos de display são:
    

#### Block (display: block):

   O elemento é formatado como um bloco retangular e ocupa todo o espaço horizontal disponível em seu contêiner. Ele inicia em uma nova linha e empurra outros elementos abaixo dele. É usado para criar elementos que se estendem horizontalmente por toda a largura do contêiner, como parágrafos, cabeçalhos (h1, h2, etc.) e divisões (div).
<br>

#### Inline (display: inline):

   O elemento é formatado como uma caixa em linha e ocupa apenas o espaço necessário para o conteúdo. Ele não inicia em uma nova linha e permite que outros elementos fiquem ao seu lado, compartilhando a mesma linha. É comumente utilizado para texto e elementos de texto, como links (a), enfatizando (em, strong) e imagens (img).
<br>
    
#### Inline-block (display: inline-block):

   Esse tipo combina características de elementos em linha e em bloco. Ele se comporta como um elemento em linha, permitindo que outros elementos compartilhem a mesma linha, mas também pode ter largura e altura definidas, como elementos em bloco. É útil quando você deseja que elementos, como imagens e blocos de texto, fiquem lado a lado sem iniciar uma nova linha.
<br>
    
 #### Flex (display: flex):

   Ao aplicar display: flex a um elemento, ele se torna um contêiner flex, permitindo que seus filhos (itens flexíveis) sejam organizados em um layout flexível dentro dele. Essa abordagem facilita o posicionamento e alinhamento dos itens, tornando-os responsivos em diferentes tamanhos de tela e dispositivos.

#### Grid (display: grid):
  
  Ao aplicar display: grid a um elemento, ele se torna um contêiner de grade, permitindo criar layouts complexos e bidimensionais. Os elementos filhos podem ser organizados em linhas e colunas, oferecendo controle preciso sobre o posicionamento e o espaçamento entre eles.

#### None(display: none):

   Esse valor faz com que o elemento fique completamente oculto na página, sem ocupar nenhum espaço. Ele é útil quando você deseja remover temporariamente um elemento da exibição sem removê-lo do DOM (Document Object Model).

#### table (display:table), Table-row (display: table-row), Table-cell (display: table-cell):) 

   Esses valores permitem emular o comportamento de tabelas usando elementos HTML não relacionados a tabelas. Eles podem ser úteis em situações específicas onde uma estrutura de tabela é necessária, mas não se deseja usar elementos de tabela tradicionais.</dt>

 ### Flex direction:
   
   é uma propriedade CSS que define a direção principal dos itens flexíveis dentro do flex container. Ela pode ser configurada com quatro valores: row (disposição horizontal), row-reverse (disposição horizontal em ordem inversa), column (disposição vertical) e column-reverse (disposição vertical em ordem inversa).

 ### Justify-content 
    
   é uma propriedade CSS aplicada ao flex container que define como os itens flexíveis serão distribuídos ao longo do eixo principal. Ela controla o espaçamento entre os itens flexíveis e o alinhamento do próprio conjunto de itens. Alguns valores comuns incluem: flex-start (alinhar ao início do eixo), flex-end (alinhar ao final do eixo), center (centralizar ao longo do eixo), space-between (espaçar igualmente entre os itens) e space-around (espaçar igualmente ao redor dos itens).
   
   justify-content

flex-start: Os itens se alinham ao lado esquerdo do contêiner.

flex-end: Os itens se alinham ao lado direito do contêiner.

center: Os itens se alinham no centro do contêiner.

space-between: Os itens são exibidos com espaçamento igual entre eles.

space-around: Os itens são exibidos com espaçamento igual ao redor deles.

 #### Jogo do sapinho para aprender a posicionar os intens  <a href="https://flexboxfroggy.com/">Sapinho</a>
 
 ### Align-items 
   
   é outra propriedade CSS aplicada ao flex container que define como os itens flexíveis serão alinhados ao longo do eixo transversal. Ela controla o posicionamento vertical dos itens flexíveis dentro do contêiner. Alguns valores comuns incluem: flex-start (alinhar ao topo do contêiner), flex-end (alinhar à base do contêiner), center (centralizar verticalmente no contêiner), baseline (alinhar pela linha de base) e stretch (alongar os itens para preencher a altura total do contêiner).

Em resumo, o flexbox é uma poderosa técnica de layout CSS que permite criar designs flexíveis e responsivos, utilizando o display flex para transformar um elemento em um contêiner flex. A propriedade flex-direction define a direção principal dos itens dentro desse contêiner, enquanto justify-content e align-items controlam o espaçamento e o alinhamento ao longo dos eixos principal e transversal, respectivamente.

### Pseudo-classes:

 first-of-type: Seleciona o primeiro elemento de seu tipo entre seus irmãos. Por exemplo, selecionará o primeiro elemento entre outros elementos irmãos.p:first-of-type<p><p>

nth-of-type: Seleciona elementos de um tipo específico com base em seu índice entre irmãos. Ele usa a palavra-chave para representar uma fórmula, como ou . Por exemplo, seleciona todos os elementos pares.n2n3n+1p:nth-of-type(2n)<p>

last-of-type: Seleciona o último elemento de seu tipo entre seus irmãos. Semelhante ao , mas seleciona o último.first-of-type

first-child: Seleciona o primeiro elemento filho de seu pai. Isso não se importa com o tipo; ele só olha para a posição do elemento.

last-child: Seleciona o último elemento filho de seu pai. Semelhante ao , mas seleciona o último.first-child

nth-child: seleciona elementos com base em seu índice entre irmãos, independentemente do tipo de elemento. Como , ele também usa a palavra-chave.nth-of-typen

nth-last-child: Seleciona elementos com base em seu índice entre irmãos, contando a partir do final. É semelhante ao , mas a contagem começa a partir do último elemento.nth-child

hover: Aplica estilos a um elemento quando o usuário passa o mouse sobre ele com o cursor.

 ### Pseudo-elementos:

 ::first-letter: Seleciona a primeira letra de um elemento de nível de bloco e permite que você aplique estilos especificamente a essa primeira letra. Use em CSS (observe os dois pontos) ao definir esse estilo.::first-letter

::first-line: Seleciona a primeira linha de um elemento de nível de bloco e permite que você aplique estilos especificamente a essa primeira linha. Use em CSS (observe os dois pontos) ao definir esse estilo.::first-line

::before: Insere o conteúdo antes do elemento selecionado. Este conteúdo é puramente decorativo e não faz parte do documento HTML. É comumente usado para adicionar elementos decorativos usando CSS.

::after: Insere conteúdo após o elemento selecionado. Como , o conteúdo é puramente decorativo e adicionado usando CSS.::before

<<<<<<< HEAD
Essas pseudoclasses e pseudoelementos fornecem maneiras poderosas de estilizar e segmentar elementos específicos e seus estados dentro de sua página da Web. Lembre-se de usá-los com cuidado e sempre verificar a compatibilidade do navegador, pois alguns navegadores mais antigos podem não suportar certos pseudo-elementos ou pseudo-classes.

#### :hover: é uma pseudoclasse que é aplicada a um elemento quando o usuário passa o mouse sobre ele com o ponteiro do mouse. É comumente usado para alterar a aparência de links, botões e outros elementos interativos quando o usuário interage com eles.:hover
Exemplo:
Suponha que você tenha um elemento button em seu HTML como este:

html

<button class="hover-button">Click Me</button>

Você pode aplicar estilos a esse botão quando ele estiver pairando sobre o CSS usando isto:

css

.hover-button:hover {
  background-color: #007bff;
  color: #fff;
  cursor: pointer;
}

Neste exemplo, quando o usuário passa o mouse sobre o botão, a cor do plano de fundo será alterada para azul () e a cor do texto mudará para branco ().#007bff#fff

#### :visited: é uma pseudo-classe usada especificamente para estilizar links visitados. Ele permite que você aplique estilos diferentes a links que o usuário já visitou em comparação com links que ele ainda não visitou. Isso geralmente é usado para fornecer feedback visual aos usuários sobre os links nos quais eles clicaram.:visited
Exemplo:
Suponha que você tenha alguns elementos âncora (link) em seu HTML como este:

html

< a class="visited-link" href="https://www.example.com">Visited Link</a>
< a class="unvisited-link" href="https://www.example.com">Unvisited Link</a>
Você pode aplicar estilos aos links visitados e não visitados usando CSS da seguinte maneira:

css

.visited-link:visited {
  color: purple;
}

.unvisited-link {
  color: blue;
}

Neste exemplo, o link visitado aparecerá na cor roxa e o link não visitado aparecerá na cor azul. Uma vez que o usuário clica no link não visitado, ele mudará para roxo, pois corresponderá à pseudoclasse.:visited

É importante notar que a pseudoclasse tem certas limitações devido a preocupações com a privacidade. Por motivos de segurança, os navegadores podem restringir os estilos que você pode aplicar aos links visitados para evitar possíveis ataques que possam revelar o histórico de navegação de um usuário. Essas restrições geralmente impedem a manipulação de propriedades que poderiam expor essas informações, como alterar a cor de plano de fundo do link.:visited
=======
nth-child(even) é um pseudo-seletor que seleciona os elementos que são filhos de seus pais e possuem um número de ordem par (linha par).

nth-child(odd) é um pseudo-seletor que seleciona os elementos que são filhos de seus pais e possuem um número de ordem ímpar (linha ímpar).

Essas pseudoclasses e pseudoelementos fornecem maneiras poderosas de estilizar e segmentar elementos específicos e seus estados dentro de sua página da Web. Lembre-se de usá-los com cuidado e sempre verificar a compatibilidade do navegador, pois alguns navegadores mais antigos podem não suportar certos pseudo-elementos ou pseudo-classes.

### 8- Aprenda a construir um web site responsivo.

Tópicos
<header>
<section>
<article>
<nav>
<aside>
<main>
<figure>
<footer>
<a>
<em>
<strong>
<cite>
<q>
<time>
Exemplo prático
header
O <header> é utilizado para representar o cabeçalho de um documento ou seção declarado no HTML. Nele podemos inserir elementos de <h1> a <h6>, até elementos para representar imagens, parágrafos ou mesmo listas de navegação.

Exemplo de uso de <header>:

<header>
     <h1>Título da página</h1>
     <h2>Subtítulo da página</h2>
</header>

Run
Nota: Diferentemente da tag <head>, é possível declarar mais de um <header> por página.
section
O elemento <section> representa uma seção dentro de um documento e geralmente contém um título, o qual é definido por meio de um dos elementos entre <h1> e <h6>. Podemos utilizar o <section>, por exemplo, para descrever as seções/tópicos de um documento.

Exemplo de uso de <section>:

<section>
    <h3>Seção 1</h3>

    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</section>

Run
article
Utilizamos o elemento <article> quando precisamos declarar um conteúdo que não precisa de outro para fazer sentido em um documento HTML, por exemplo, um artigo em um blog. É recomendado identificar cada <article> com um título.

Exemplo de uso de <article>:

<article>
    <h3>Título do artigo 1</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</article>
<article>
    <h3>Título do artigo 2</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</article>

Run
nav
O elemento <nav> é utilizado quando precisamos representar um agrupamento de links de navegação, que, por sua vez, são criados com os elementos <ul>, <li> e <a>.

Exemplo de uso de <nav>:

<nav>
 <ul>
 <li><a href=”#”>pagina 1</a></li>
 <li><a href=”#”>pagina 2</a></li>
 <li><a href=”#”>pagina 3</a></li>
 <li><a href=”#”>pagina 4</a></li>
 </ul>
</nav>

Run
Nota: Podemos declarar o <nav> em qualquer lugar do documento que contenha uma lista de links, inclusive no <header>.
aside
O elemento <aside> é utilizado quando precisamos criar um conteúdo de apoio/adicional ao conteúdo principal. Por exemplo, ao falar de HTML semântico, podemos indicar ao leitor outros conteúdos sobre a linguagem HTML como sugestão de leitura complementar.

Exemplo de uso de <aside>:

<aside>
  <nav>
    <ul>
        <li>Link 1</li>
        <li>Link 2</li>
        <li>Link 3</li>
        <li>Link 4</li>
     </ul>
  </nav>
</aside>

Run
main
O elemento <main> especifica o conteúdo principal e, consequentemente, de maior relevância dentro da página. Para ser considerada bem construída, uma página deve apresentar apenas um conteúdo principal.

Exemplo de uso de <main>:

<main>
  <h2>Titulo</h2>

  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>

  <article>
     <h3>Subtítulo</h3>
        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum...</p>
   </article>
</main>

Run
Nota: O conteúdo declarado dentro da tag <main> deve ser único no documento, incluindo links e imagens.
figure
O elemento <figure> é uma marcação de uso específico para a inserção de uma figura. Para incluir a descrição dessa figura, podemos utilizar o elemento <figcaption>.

Exemplo de uso de <figure>:

<figure>
  <img src=”http://meusite.com.br/assets/imagem.jpg” alt=”Imagem”>
</figure>

Run
Exemplo de uso de <figure> com <figcaption>:

<figure>
   <img src=”http://meusite.com.br/assets/imagem.jpg” alt=”Imagem”>

   <figcaption>Figura 1. Imagem</figcaption>
</figure>

Run
footer
O elemento <footer> representa um rodapé de um documento, como a área presente no final de uma página web. Normalmente é utilizado para descrever informações de autoria, como nome e contato do autor, e data de criação do conteúdo.

Exemplo de uso de <footer>:

<footer>
     <p>Escrito por Estevão Dias</p>
     <p>Publicado em 25/03/2017 </p>
</footer>

Run
Semântica no nível do texto
Além da semântica estrutural, o HTML nos permite descrever o significado de um conteúdo em nível de texto utilizando um conjunto de elementos semânticos. Assim, é possível, por exemplo, destacar os trechos de texto que devem receber algum tipo de destaque.

a
A principal função do elemento <a> é descrever um link, conectando os diversos documentos de um site e permitindo a navegação por esse conteúdo. Normalmente esses documentos estão relacionados por compartilharem um assunto em comum.

Exemplo de uso de <a>:

<a href=”http://www.devmedia.com.br” alt=”DevMedia”>DevMedia</a>

Run
em
O elemento <em> é utilizado quando desejamos enfatizar um trecho ou palavra no texto, indicando que ela contribui de forma mais relevante para o sentido/compreensão do conteúdo.

Exemplo de uso de <em>:

<p>Você <em>tem certeza</em> que essa definição está correta?</p>

Run
Dessa forma enfatizamos o trecho mais relevante da pergunta.

strong
O elemento <strong> também é utilizado para destacar uma parte do texto. Sua principal diferença em relação ao elemento <em> é que <em> pode alterar o propósito de uma frase, como vimos anteriormente.

Exemplo de uso de <strong>:

<p>Compreender esses elementos HTML é importante porque
<strong>possibilita o desenvolvimento de soluções web modernas</strong>.</p>

Run
cite e q
O elemento <cite> é utilizado para declarar que naquele trecho há uma citação, isto é, um trecho de texto que não foi escrito pelo autor do conteúdo. Normalmente utiliza-se o <cite> em conjunto com o elemento <q>, responsável por apresentar o conteúdo retirado de outra fonte.

Exemplo de uso de <cite> e <q>:

<p>
<q>Lorem ipsum dolor sit amet, consectetur </q> - <cite>http://br.lipsum.com/</cite>.
</p>

Run
time
O elemento <time> é utilizado para representar datas. Assim, caso seja necessário informar a data em que um conteúdo foi escrito, podemos declarar a tag <time> e acrescentar a ela o atributo datetime para escrever a data de forma padronizada.

<time datetime=”2017-04-07”>4/7</time>

<header>: Usada para definir o cabeçalho da página ou de uma seção específica.
<nav>: Usada para definir uma seção de navegação.
<main>: Usada para definir o conteúdo principal da página.
<section>: Usada para agrupar um conteúdo relacionado e significativo.
<article>: Usada para definir um conteúdo independente e autônomo, como um post de blog ou um artigo.
<aside>: Usada para definir um conteúdo complementar, que é relacionado, mas não faz parte do conteúdo principal.
<footer>: Usada para definir o rodapé da página ou de uma seção específica.

#### Trabalhando com Design Responsivo em HTML5

Dentre as características essenciais a um site responsivo, destacam-se:

Adaptar o layout da página de acordo com a resolução em que está sendo visualizada;
O layout deve ser fluido e não deve fazer uso de medidas fixas, possibilitando a adaptação natural ao dispositivo em questão;

Simplificar elementos da tela para dispositivos móveis, onde o usuário normalmente tem menos tempo e menos atenção durante a navegação;

Redimensionar as imagens e vídeos para que não sobrecarreguem a transferência de dados e também para que se adaptem ao dispositivo garantindo que os mesmos se apresentem de forma nítida, sem cortes e que não façam uso da barra de rolagem para serem visualizados;

Ocultar ou remover elementos desnecessários nos dispositivos menores;
Adaptar o tamanho de botões, links e menus para interfaces touch onde o ponteiro do mouse é substituído pelo dedo do usuário.

Mobile First é uma estratégia de desenvolvimento que diz que todo o planejamento de um projeto web deve iniciar pelos dispositivos móveis e somente depois gradualmente para os outros dispositivos, até chegar nos notebooks e desktops.v

Meta Tag Viewport
O termo viewport corresponde à área disponível para exibição de conteúdo que cada dispositivo possui.

O valor do viewport varia de acordo com o dispositivo. Por exemplo, em um computador, o viewport corresponde a área (altura e largura) em pixels ocupada pelo navegador. Portanto, quando o navegador é redimensionado para uma tela menor, automaticamente o seu viewport também se torna menor.

Consequentemente, essa característica causa diversos problemas em sites já projetados para o mundo mobile. Isso porque o dispositivo irá encolher o site para exibi-lo de acordo com a largura de 980 pixels, o que impossibilita o funcionamento das regras responsivas, cujo problema a Meta Tag Viewport visa solucionar a partir de agora.

A meta tag viewport possui um formato semelhante ao de outras tags meta, conforme podemos observar a seguir:

<meta name="viewport"content="">

Na declaração do content é possível especificar uma diversidade de parâmetros, tais como:

width: define a largura do viewport.
height: define a altura do viewport.
initial-scale: define a escala inicial (zoom) do viewport.
Para que possamos assegurar o funcionamento das regras responsivas em todos os dispositivos, devemos declarar que a largura do viewport será igual à mesma largura do dispositivo e que a escala inicial (zoom) é 1, conforme demonstrado a seguir:

<meta name="viewport" content="width=device-width, initial-scale=1.0">

#### Media Type é o responsável por designar quais regras CSS serão interpretadas por um determinado tipo de dispositivo, oferecendo a melhor apresentação possível do conteúdo sem a necessidade de alteração do mesmo.

Dentre os diversos tipos de Media Type, alguns se destacam e são importantes ao conhecimento do leitor:

All: Se refere a todos os tipos de dispositivos.
Braille: Se refere aos dispositivos táteis.
Embossed: Se refere aos dispositivos que imprimem em braille.
Handheld: Se refere aos dispositivos de mão, normalmente com telas pequenas de baixa resolução e largura de banda limitada.
Print: Se refere aos dispositivos de impressão.
Projection: Se refere a apresentações do tipo slides.
Screen: Se refere a monitores ou dispositivos com telas coloridas e resolução adequada.
Speech: Se refere a sintetizadores de voz ou leitores de tela.
TTY: Se refere a terminais, teletypes e dispositivos portáteis com display limitado.
TV: Se refere a televisores ou dispositivos com baixa resolução, quantidade de cores e scroll limitado.

#### Media Queries 

aspect-ratio	
Se refere à proporção entre os valores de largura e altura. Os valores são compostos pela divisão da largura/valor da altura. Não aceita os prefixos min/max.

device-aspect-ratio
Se refere à proporção entre os valores de largura e altura do dispositivo. Os valores são compostos por valor da largura/valor da altura. Não aceita os prefixos min/max.

Color	
Se refere ao número de bits por cor. Os valores são numéricos. Aceita os prefixos min/max.

color-index
	Se refere ao número de entradas na tabela de pesquisa de cores do dispositivo de saída. Os valores são numéricos. Aceita os prefixos min/max.

Height
	Se refere à altura da janela do navegador. Os valores são medidas de comprimento. Aceita os prefixos min/max.

device-height	
  Se refere à altura da mídia. Os valores são medidas de comprimento. Aceita os prefixos min/max.

Width
	Se refere à largura da janela do navegador. Os valores são medidas de comprimento. Aceita os prefixos min/max.

device-width	
  Se refere à largura da mídia. Os valores são medidas de comprimento. Aceita os prefixos min/max.

Grid
	Se refere ao tipo de dispositivo, se é orientado a bitmaps ou grids. Os valores são 1 para dispositivos orientados a grid e 0 para dispositivos orientados a bitmap. Não aceita os prefixos min/max.

Monochrome	
  Se refere ao número de bits por pixel em um buffer de quadros monocromáticos. Os valores são numéricos. Aceita os prefixos min/max.

Orientation
	Se refere à orientação da mídia. Os valores são portrait para vertical / retrato e landscape para horizontal / paisagem. Não aceita os prefixos min/max.

Resolution	
  Se refere à resolução, densidade por pixel, utilizada pelo dispositivo. Os valores são em DPI ou DCM. Aceita os prefixos min/max.

Scan
	Se refere ao tipo de formação de imagens para televisores. Os valores são progressive ou interlace. Não aceita os prefixos min/max.

Para realizar a combinação entre os Media Types e as Media Features que formam as regras condicionais e resultam nas Media Queries, são utilizados os operadores. Dentre eles, podemos destacar:

#### not:
 É utilizado quando se deseja que o resultado de uma determinada expressão seja o oposto ao real. Veja na Listagem 1 um exemplo do seu uso.

#### only:
 É utilizado quando se deseja prevenir que navegadores antigos que não suportam Media Features tentem processar a expressão. Na Listagem 2 podemos ver um exemplo fiel disso.

#### and: 
 É utilizado em todas as Media Queries, tendo como função primária ser o elo entre o Media Type e a Media Feature. É também responsável pelas expressões múltiplas, isto é, quando usamos mais de uma Media Feature para compor a expressão.

#### “,“: 
 É utilizado para juntar duas ou mais expressões diferentes que deverão executar um mesmo conjunto de regras. Funciona como um “ou” condicional na lógica de programação.

#### Exemplo de utilização do operador lógico “not”.

@media not print and (min-width: 768px) {
  body {
      background-color: #FF0000;
  }
}

Neste exemplo, todos os dispositivos que não forem do tipo print com largura mínima de 768 pixels terão a cor de fundo do corpo do documento vermelha. Sem o uso do operador not, o resultado seria o oposto, e a cor de fundo do corpo do documento seria vermelha para todos os dispositivos do tipo print com a largura mínima de 768 pixels.

#### Exemplo de utilização do operador lógico “only”.

@media only screen and (max-width: 320px) {
  h1 {
      text-decoration: underline;
  }
}

Já neste exemplo, em dispositivos do tipo screen que tenham largura até 320 pixels, os elementos h1 terão seus textos exibidos com underline. Sem o operador only, a expressão iria ser executada por todos os dispositivos, e no caso de dispositivos que não suportam Media Features, somente o Media Type seria reconhecido e as mesmas seriam ignoradas.

O que resultaria na execução da regra referente ao h1 em dispositivos nos quais esta não deveria ser executada.

Na Listagem 3 temos uma expressão múltipla relacionada aos dispositivos do tipo screen, onde duas Media Features são utilizadas dentro de uma mesma expressão. Uma Media Feature corresponde à largura mínima de 320 pixels e outra à largura máxima de 480 pixels. Portanto, caso positiva, o elemento header terá a largura de 100% em dispositivos do tipo screen com a largura entre 320 e 480 pixels.

#### Exemplo de utilização do operador lógico “and”.

@media only screen and (min-width: 320px) and (max-width: 480px) {
  header {
      width: 100%;
  }
}

Na Listagem 4 há duas expressões diferentes, uma para dispositivos do tipo handheld com largura máxima de 500 pixels e outra para dispositivos do tipo screen com largura máxima de 620 pixels.

Ambas as expressões são totalmente independentes uma da outra, mas será executada, caso positivas, a mesma regra CSS, que consiste justamente em deixar negrito todo o texto existente dentro de um elemento de parágrafo p.

#### Exemplo de utilização do operador lógico “,”.

@media only handheld and (max-width: 500px), only screen and (max-width: 620px) {
  p {
      font-weight: bold;
  }

### Breakpoints
 Os breakpoints são delimitadores das regras CSS para atenderem diferentes especificações, que são criados pelo uso de Media Queries. Tratam-se também de uma forma de organizar o uso das Media Queries, visando a criação de blocos previamente definidos de acordo com os dispositivos que serão suportados, e onde serão inseridas as respectivas regras CSS.

 Isso evitará, desta forma, a utilização de diversas regras pontuais para a resolução de casos específicos.

 Não existe um número ou um grupo exato de breakpoints a serem utilizados. A definição dos breakpoints está diretamente ligada a características especificas do site em questão, como o conteúdo e os dispositivos que serão suportados.

 Portanto, um novo breakpoint deve ser criado sempre que a apresentação do conteúdo em determinado dispositivo não oferecer a melhor experiência possível ou simplesmente não for satisfatória.

 #### Exemplo de uso dos breakpoints.

/* INICIO REGRAS PARA TODOS OS DISPOSITIVOS */
INSIRA REGRAS CSS AQUI!
/* FIM REGRAS PARA TODOS OS DISPOSITIVOS*/

/* INICIO REGRAS PARA DISPOSITIVOS DE IMPRESSÃO */
@media print {
  INSIRA REGRAS CSS AQUI!
}
/* FIM REGRAS PARA DISPOSITIVOS DE IMPRESSÃO */

/* INICIO REGRAS PARA DISPOSITIVOS COM LARGURA MÍNIMA DE 320 PIXELS. POR EXEMPLO: SMARTHPHONES */
@media screen and (min-width: 320px) {
  INSIRA REGRAS CSS AQUI!
}
/* FIM REGRAS PARA DISPOSITIVOS COM LARGURA MÍNIMA DE 320 PIXELS. POR EXEMPLO: SMARTHPHONES */

/* INICIO REGRAS PARA DISPOSITIVOS COM LARGURA MÍNIMA DE 768 PIXELS. POR EXEMPLO: TABLETS */
@media screen and (min-width: 768px) {
  INSIRA REGRAS CSS AQUI!
}
/* FIM REGRAS PARA DISPOSITIVOS COM LARGURA MÍNIMA DE 768 PIXELS. POR EXEMPLO: TABLETS */

/* INICIO REGRAS PARA DISPOSITIVOS COM LARGURA MÍNIMA DE 1024 PIXELS. POR EXEMPLO: COMPUTADORES DESKTOP E NOTEBOOKS */
@media screen and (min-width: 1024px) {
  INSIRA REGRAS CSS AQUI!
}
/* FIM REGRAS PARA DISPOSITIVOS COM LARGURA MÍNIMA DE 1024 PIXELS. POR EXEMPLO: COMPUTADORES DESKTOP E NOTEBOOKS */

Veja que a implementação desse tipo de estrutura é muito semelhante a estruturas já existentes em outras ferramentas e linguagens de programação, como o Visual Studio, por exemplo.

Além de trazer um ar de organização ao conteúdo dos arquivos CSS, ele também ajuda na hora de buscar por determinadas regras ou selecionar um conjunto delas para alteração.

Colocando em prática
Agora que já conhecemos em detalhes o que são os termos Media Types, Media Features e Media Queries, é hora de colocar em prática o conhecimento adquirido. Neste exemplo, vamos criar um site responsivo que deverá apresentar quatro versões de layout diferentes. A saber:

Primeira versão: Se refere aos dispositivos considerados pequenos, com largura até 480 pixels;
Segunda versão: Se refere aos dispositivos considerados médios, com largura maior que 480 pixels e até 1024 pixels;
Terceira versão: Se refere aos dispositivos considerados grandes, com largura maior que 1024 pixels;
Quarta versão: Se refere aos dispositivos de impressão.
Todas as quatro versões possuirão características especificas. Primeiramente, crie um documento HTML e nomeie-o como “index.html”, e adicione o conteúdo presente na Listagem 6, que se refere a estrutura inicial da página, contendo apenas algumas declarações das tags que vimos anteriormente, bem como um título e uma tag h1 no corpo da página.

Listagem 6. Marcação HTML inicial.

<!DOCTYPE html>
<html lang="pt-br">
  <head>

      <!-- INICIO META TAGS -->
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <!-- FIM META TAGS -->

      <!-- INICIO TITULO DO DOCUMENTO -->
      <title>Teste Layout Responsivo</title>
      <!-- FIM TITULO DO DOCUMENTO -->

  </head>
  <body>

      <!-- INICIO TITULO DA PÁGINA -->
      <h1 class="titulo">Teste Layout Responsivo</h1>
      <!-- FIM TITULO DA PÁGINA -->

  </body>
</html>

/* INICIO REGRAS CSS REFERENTES À PRIMEIRA VERSÃO */
@media only screen and (max-width: 480px) {

  body {
      background-color: #D46A6A;
      color: #FFF;
  }

  .conteudo-dispositivo.pequeno {
      display: block;
  }

}
/* INICIO REGRAS CSS REFERENTES À SEGUNDA VERSÃO */
@media only screen and (min-width: 481px) and (max-width: 1024px) {

  body {
      background-color: #758AA8;
      color: #FFF;
  }

  .conteudo-dispositivo.medio {
      display: block;
  }

}

/* INICIO REGRAS CSS REFERENTES À TERCEIRA VERSÃO */
@media only screen and (min-width: 1025px) {

  body {
      background-color: #D4CE6A;
      color: #000;
  }

  .conteudo-dispositivo.grande {
      display: block;
  }

}
/* INICIO REGRAS CSS REFERENTES À QUARTA VERSÃO */
@media print {

  .titulo {
      margin: 0 0 50px;
      text-align: left;
  }

  .conteudo-dispositivo {
      text-align: left;
  }

  body {
      background-color: #FFF;
      color: #000;
  }

  .conteudo-dispositivo.impressao {
      display: block;
  }

}

#### Media types
  A Listagem 1 apresenta um exemplo de uso do @media que altera a cor do texto dependendo do tipo de mídia. Dessa forma, quando a página for acessada de um browser, visualizaremos a cor azul; já em modo de impressão, visualizaremos a cor vermelha.

@media screen {
    body {
        color: blue;
    }
}
@media print {
    body {
        color: red;
    }
}

#### Media Queries

Os operadores not e only permitem negar um tipo de mídia, ou especificar que apenas determinado tipo seja atendido, respectivamente. Por exemplo, a expressão not speech faria com que as regras não fossem aplicadas a leitores de tela, enquanto que only screen faria com que apenas telas fossem atendidas.

Por sua vez, o operador and faz a ligação entre o tipo de mídia e o filtro adicional que será especificado entre parênteses, no lugar de query. Nesse ponto podemos utilizar as diversas propriedades da mídia, como orientação, largura e altura, para obter os resultados desejados.

Na Listagem 2 temos um exemplo de uso das media queries. Com esse código, aplicamos o plano de fundo azul para páginas com até 640px de largura e vermelho para aquelas com até 480px de largura. Acima de 640px, o comportamento padrão será assumido, ou seja, será mantida a página branca.

@media screen and (max-width: 640px){
    body {
        background-color: blue;
    }
}
@media screen and (max-width: 480px){
    body {
        background-color: red;
    }
}

#### Reset específico para alguns elementos

O reset do CSS dos elementos é uma operação bastante simples, porém, muitas vezes acabamos esquecendo desse passo quando começamos a desenvolver de forma responsiva. No geral, isso leva a designs “quebrados” em alguns navegadores, mas que potencialmente funcionam bem em outros.

No caso de nosso exemplo, precisamos resetar apenas os elementos <html>, <body> e <h2>, uma vez que estamos utilizando somente eles. Dessa forma, um CSS como o da Listagem 1 seria suficiente.

html, body, h2
{
    margin: 0;
    padding: 0;
}

#### Reset para todos os elementos

Caso a complexidade do HTML aumente, podemos concluir que a abordagem anterior pode prejudicar a construção da interface. Seria necessário controlar o reset de muitos elementos. Diante disso, o CSS traz uma outra possibilidade de reset, mais simples, e que permite que tenhamos todos os elementos do DOM como alvo: através do operador *. Vejamos um exemplo no código abaixo:

* { margin: 0; padding: 0; }
Com isso, ao invés de informarmos cada elemento do DOM que será resetado, com o operador * determinamos que todos eles o serão. Assim, é garantido que, independentemente do que for inserido no HTML, teremos um design responsivo sem diferenças entre os navegadores.