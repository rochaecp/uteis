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
- Na camada de cima: seleciona camiseta usando seleção livre + enter.
- Cores -> colorizar -> selecione as cores.

## Criar um gif

- Coloque uma imagem por camada.
- Ctrl + Shift + e -> arquivo.gif -> selecione tempos

## Criar uma camada a partir de uma seleção

- Selecione uma região.
- Ctrl + x, Ctrl + v
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
	- Filtro -> desfocar -> desfocagem gaussiana (inserir valor 10)
- Selecione a camada de cima, adicionar canal alfa, borracha (diminuir opacidade da borracha), apagar machas


## Adicionar pincéis

- Acessar algum site de brushes, adicionar ao gimp na pasta brushes.
- Criar um png com um novo pincel. Exportar como .gbr e adicionar ao gimp na pasta brushes.