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

 ### Align-items 
   
   é outra propriedade CSS aplicada ao flex container que define como os itens flexíveis serão alinhados ao longo do eixo transversal. Ela controla o posicionamento vertical dos itens flexíveis dentro do contêiner. Alguns valores comuns incluem: flex-start (alinhar ao topo do contêiner), flex-end (alinhar à base do contêiner), center (centralizar verticalmente no contêiner), baseline (alinhar pela linha de base) e stretch (alongar os itens para preencher a altura total do contêiner).

Em resumo, o flexbox é uma poderosa técnica de layout CSS que permite criar designs flexíveis e responsivos, utilizando o display flex para transformar um elemento em um contêiner flex. A propriedade flex-direction define a direção principal dos itens dentro desse contêiner, enquanto justify-content e align-items controlam o espaçamento e o alinhamento ao longo dos eixos principal e transversal, respectivamente.
