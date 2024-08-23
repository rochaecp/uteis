# Gimp 

## Atalhos

- Ctrl \+ Scroll: Zoom in, Zoom out  
- Space \+ move mouse: move view  
- Ctrl \+ Shift \+ a: remove a seleção  
- Shift \+ click (com lapis, caneta): traços retas

## Interface

- Janelas -> Diálogos de encaixe: inclui novas janelas.   
- O Gimp mantém a última configuração de janelas que foi feita.

## Criar um novo projeto

- Arquivo -> Novo  
    - Modelo (largura x altura) - Ex.: 640 x 400 px.  
    - Opções avançadas (resolução, espaços de cor).  
        - Preencher com (usar branco).

## Resolução

- 300 em x e y - boa qualidade

## Abrir diversas imagens

- Arquivo -> abrir como camadas

## Ferramenta Seleção retangular: 

- Cria retangulo na região a ser selecionada.  
- Modificações só poderão ser feitas nessa região.  
- Ctrl \+ Shift \+ a -> remove a seleção

## Ferramenta Seleção elíptica

- Seleciona um olho.   
- Opções de ferramentas -> Modo: adicionar à seleção atual (ou shift)

## Ferramenta Seleção Livre

- Uso: clicando em diversos pontos até formar superfície fechada.  
- Uso: clicando e arrastando \+ enter no fim.  
- Ver ferramentas de seleção livre - adicionar seleção, intersecção etc

## Ferramenta de Vetores

- Insira uma imagem  
- Clique em vários pontos para criar o vetor - permite arrastar pontos.  
    - Clique num ponto e depois no proximo para conectá-los.  
- Ferramentas -> Edição - permite inserir mais pontos.  
- Adicionar um ponto: Ctrl \+ click  
- Remover um ponto: Segure Ctrl e Shift \+ clique sobre ponto.  
- Após criar o últim ponto segure Ctrl e clique no primeiro. Enter: cria seleção.

## Ferramenta de Movimento

- Opções de ferramenta -> mover a camada atual

## Ferramenta de Corte

- Seleciona parte da camada \+ enter: gera camada com a seleção.  
    - Opções de ferramentas -> somente camada atual

## Ferramenta de clonagem

- Insere uma forma. Clica em Ferramenta de clonagem, Ctrl \+ clique na forma.  
- Clica em regiões do desenho. A forma criada será clanada.

## Remover canal alfa

- Ao apagar partes da camada nao remove o fundo e sim pinta com a cor de fundo selecionada na paleta.

## Colocar textura em texto

- Cria texto, botao direito na camada do texto, alfa para seleção, vai na camada da textura  
- ctrl c, ctrl v, para nova camada 

## Menu cores

- Equilíbrio de cores - atua sobre um conjunto de cores  
- Matiz e saturação - atua sobre um conjunto de cores  
    - Permite manipular uma cor específica dentro de uma imagem  
- Colorizar - aplica filtro sobre a região

## Acessar plugins

- Arquivo -> criar -> logos, botoes, etc ... muito legal\!

# Gimp - Diversos

## Pintar uma camiseta de outra cor

- Abra o Gimp, arraste uma imagem para a área de trabalho.  
- Nova camada (preenchimento transparente) - acima da camada da foto. É como uma folha transparente sobre a imagem.  
- Na camada criada: Pincel (cor azul) - pinta a camiseta.  
    - Opções de ferramentas: edita o tam do pincel.  
- Na camada criada: Modo -> cor - vai mesclar as cores.  
- Na camada criada: Borracha - tira o excesso.  
- Usar uma camada para cada efeito.

## Pintar uma camiseta de outra cor com colorizar

- Insere imagem, duplica camada.  
- Na camada de cima: seleciona camiseta usando seleção livre \+ enter.  
- Cores -> colorizar -> selecione as cores.

## Criar um gif

- Coloque uma imagem por camada.  
- Ctrl \+ Shift \+ e -> arquivo.gif -> selecione tempos

## Criar uma camada a partir de uma seleção

- Selecione uma região.  
- Ctrl \+ x, Ctrl \+ v  
- Em seleção flutuante -> bt dir: para nova camada.

## Remover o fundo de uma imagem

- Arquivo, abrir imagem  
- Duplicar camada, Bt dir na camada, adicionar canal alfa  
- Seleção por cor, clica em cor, deleta cor selecionada  
- Duplica camada original, adiciona canal alfa, borracha, apaga fundo copia

## Remover o fundo de uma imagem 2

- Arquivo, abrir imagem  
- Duplicar camada, seleção livre, selecionar ponto a ponto da imagem  
- Bt dir na camada, adicionar canal alfa, pressionar delete

## Remover o fundo de uma imagem com cabelo grande

- adicionar canal alfa  
- em canais: duplicar o canal azul, tirar visibilidade da foto original  
- ferramenta de exposição: marcar super-exposição, sombras, exposição 100% - pintar toda imagem  
- selecionar por cor, vai na camada original, recortar, para nova camada. pode excluir canal duplicado.

## Remover manchas (ou espinhas) num rosto

- Arquivo -> Abrir -> abra uma imagem  
- Em camadas duplique a imagem para nao danificar a original  
- Na camada de cima: Ferramenta de restauração ->   
    - pressione Ctrl na área a ser copiada (onde a pele for bonita)  
    - pinte as regioes com espinhas desfocando-as  
- Duplicar a camada modificada.  
- Na camada modificada de baixo desfocamos ela utilizando  
    - Filtro -> desfocar -> desfocagem gaussiana (inserir valor 10\)  
- Selecione a camada de cima, adicionar canal alfa, borracha (diminuir opacidade da borracha), apagar machas

## Adicionar pincéis

- Acessar algum site de brushes, adicionar ao gimp na pasta brushes.  
- Criar um png com um novo pincel. Exportar como .gbr e adicionar ao gimp na pasta brushes.

**Old**

Aula 1: 

- Tema: Pintando a blusa de uma mulher  
- Arquivo -> Novo  
    - Alta resolução: 300 x 300 pixels / cm  
    - Preencher com: branco  
    - Comentário: aparecerá em propriedades  
- Arrasta objeto para a tela: cria camada  
- Botão adiciona nova camada à imagem  
- Pintar em cima da camada criada  
- Usar a borracha para apagar excessos

Aula 2:

- Tema: 

https://www.youtube.com/watch?v=MsMIRrVORiQ\&list=PLFQlPs1NM\_-PD3S2m7mZkPf-TfJ8kYU0N\&index=2  
06:47

## 

