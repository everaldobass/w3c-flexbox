# Propriedades do Flexbox

## Elemento pai (contêiner)
- Main axis - Eixo Principal
- Crosss axis - Eixo - Secundário
- display:block; - Padrão
- display: flex; - O flex container torna-se flexível definindo a display propriedade para flex:

## As propriedades do flex container são:
- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items
- align-content

## flex-direction
##### A flex-direction propriedade define em qual direção o contêiner deseja empilhar os itens flexíveis.
- flex-direction: column; O column valor empilha os itens flexíveis verticalmente (de cima para baixo):
- flex-direction: column-reverse; - O column-reverse valor empilha os itens flexíveis verticalmente (mas de baixo para cima):
- flex-direction: row; - O row valor empilha os itens flex horizontalmente (da esquerda para a direita):
- flex-direction: row-reverse; - O row-reverse valor empilha os flex items horizontalmente (mas da direita para a esquerda):

### A propriedade flex-wrap
- flex-wrap: nowrap; - O nowrap valor especifica que os itens flexíveis não serão agrupados (esse é o padrão):
- flex-wrap: wrap; - O wrap valor especifica que os itens flexíveis serão agrupados, se necessário:
- flex-wrap: wrap-reverse; - O wrap-reversevalor especifica que os itens flexíveis serão agrupados, se necessário, na ordem inversa:

### A propriedade flex-flow
- A flex-flow propriedade é uma propriedade abreviada para definir as propriedades flex-directione flex-wrap.

### A propriedade justify-content
- justify-content: flex-start; - O flex-start valor alinha os itens flexíveis no início do contêiner (esse é o padrão)
- justify-content: center; - A justify-content propriedade é usada para alinhar os itens flexíveis:
- justify-content: flex-end; - O flex-endvalor alinha os itens flexíveis no final do contêiner:
- justify-content: space-around; O space-around valor exibe os itens flexíveis com espaço antes, entre e depois das linhas:
- justify-content: space-between; - O space-between valor exibe os itens flexíveis com espaço entre as linhas:

### A propriedade align-items
- align-items: stretch; - O stretchvalor estica os itens flexíveis para preencher o contêiner (esse é o padrão):
- align-items: center; - O center valor alinha os itens flexíveis no meio do contêiner:
- align-items: flex-start; - O flex-star tvalor alinha os itens flexíveis na parte superior do contêiner:
- align-items: flex-end; - O flex-end valor alinha os itens flexíveis na parte inferior do contêiner: - O baselinevalor alinha os itens flexíveis, como os alinhamentos de suas linhas de base:

### A propriedade align-content
- A align-contentpropriedade é usada para alinhar as linhas flexíveis.
- align-content: stretch; - O stretch valor estica as linhas flexíveis para ocupar o espaço restante (este é o padrão).
- align-content: space-between; - O space-betweenvalor exibe as linhas flexíveis com espaço igual entre elas.
- align-content: space-around; - O space-aroundvalor exibe as linhas flexíveis com espaço antes, entre e depois delas.
- align-content: center; - As centerexibições de valor exibem as linhas flexíveis no meio do contêiner
- align-content: flex-start; - O flex-start valor exibe as linhas flexíveis no início do contêiner.
-  align-content: flex-end; - O flex-endvalor exibe as linhas flexíveis no final do contêiner.

### Centralização Perfeita
- SOLUÇÃO: Defina as propriedades justify-contente align-items como centere o flex item ficará perfeitamente centralizado:

### Elementos Filhos (Itens)
- Os elementos filhos diretos de um flex container automaticamente se tornam flexíveis (flex) items.

#### As propriedades do flex item são:
- order - A propriedade order pode alterar a ordem dos itens flexíveis
- flex-grow - A flex-growpropriedade especifica quanto um flex item crescerá em relação ao resto dos flex items.
- flex-shrink - A flex-shrinkpropriedade especifica o quanto um flex item irá encolher em relação ao resto dos flex items.
- flex-basis - A flex-basispropriedade especifica o comprimento inicial de um item flexível.
- flex - A flexpropriedade é uma propriedade estenográfica para os flex-grow, flex-shrinke flex-basispropriedades.
- align-self - A align-selfpropriedade especifica o alinhamento do item selecionado dentro do recipiente flexível.







