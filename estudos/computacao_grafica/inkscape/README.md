# Inkscape

## Atalhos

| Ação | Atalho |
| :---- | :---- |
| Ajustar zoom  | Tecla numérica 5 |
| Alinhar objetos às bordas da página | Botão canto direito inferior |
| Redimensionar mantendo a proporção | Ctrl \+ redimensionar |
| Duplicar um objeto | Ctrl \+ D |
| Agrupar objetos | Ctrl \+ G |
| Dar zoom in ou zoom out | Shift \+ ou Shift - ou Ctrl \+ scroll |
| Movimentar a tela | Setas |
| Fazer objeto subir  | Page Up |
| Fazer objeto descer | Page Down |
| Alternar entre 2 janelas | Alt \+ Tab |

## Interface e ferramentas

#### Preenchimento e contorno:

- Preenchimento: edita cores e gradientes.  
    - 2 clicks sobre a linha de gradiente - adiciona pontos sobre ela (cada ponto pode ter uma cor).  
- Cor do contorno: pode ter gradiente no contorno.  
- Contorno: permite colocar ponta numa seta.

#### Ferramenta de gerenciador de camadas:

- Travar uma camada - cadeado - não permite alterar a camada.  
- Quanto mais camadas mais organizado fica o projeto.  
- Modo de mistura: misturar camadas.

#### Ferramenta Alinhar e distribuir:

- Alinhamento: "relativo à".  
- Distribuir objetos de forma equidistante.

#### Ferramenta de texto:

- Efeitos em textos   
    - Aplicar gradiente em textos;  
        - cria texto, seleciona, converter em caminhos  
- Importar imagem, digita texto sobre ela, seleciona ambos, clip \=\> faz texto ter textura da imagem  
    - Permite botao direito, retirar recorte  
- Digita texto, seleciona, filtros -\> aplicar diferentes filtros

#### Diversos:

- Cria uma elipse com cor sólida, duplica ela, na segunda poe cor mais clara, gradiente radial, poe uma sobre a outra  
- Poligono - seleciona o número de pontos - cria triangulos, ...  
- Editor de nós, seleciona objeto, marca opção converter objeto selecionado em caminhos - modifica vérticies do objeto :D  
- Modificando o vértice do objeto com o CTRL pressionado mantém a simetria  
- Clica no primeiro, clica no que tu quer cortar, vai em caminho, diferença - corta o objeto  
- Criação do olho - muito legal\! usou gradiente  
- Seleciona objeto - espelhamento horizontal e vertical  
- Duplica objeto, segura CTRL e move ele - deixa objeto alinhado  
- Ferramenta lápis - suavização: traços mais limpos

#### Ferramenta editor de nós:

- Cria um retangulo - converte objeto selecionado em caminhos - 2 clicks: cria nó  
- Botao excluir nós selecionados  
- Quebra caminho remove os nós   
- Seleciona 2 vértices - botao unir nós selecionados - vira um triângulo    

#### Ferramenta ajustador:

- Empurra regiões de caminho em qualquer direção - cria cavidades no objeto - bem legal  
- Atrai caminhos - puxa bordas do desenho pra fora

#### Caminho:

-Cria 2 objetos (retangulo e circunferencia), clica no primeiro, shif \+ clica no segundo e:  
    - Arquivo, importar, seleciona imagem, caminho, rasterizar bitmap, por cores, seleciona objeto, desagrupar  
    - Caminho, união  
    - Caminho, diferença - apaga o objeto de cima e tudo o que ele sobrepor no de baixo  
    - Caminho, interseção - pega tudo que pertence ao mesmo tempo aos 2 objetos  
    - Caminho, exclusão - exclui tudo em comum  
    - Caminho, divisão - permite cortar um objeto - tirar uma fatia de uma pizza por exemplo  
    - Caminho, combinar - posso separar os objetos (unica diferença do uniao)

#### Objeto: 

- Objeto - propriedades do objeto - id, rótulo, título(ex.: cabeçalho, rodapé, adesivo), ocultar, bloquear  
- Objeto - clip - permite remover fundo  
- Objeto - mascara - mantem objeto anterior  
- cria retangulo - objeto - converter em guias - da pontos de referência para o objeto nao ficar torto  
    - É melhor do que ir na régua e em puxar guia  
- Objeto - exibir todos ou desbloquear todos    
- Objeto - transformações - permite numericamente realizar transformações de movimento, escala, giro, inclinação em objetos  
- Objeto - organizar - permite alinhar e distribuir de modo bem legal  
- Camadas - modo de mistura - permite misturar cores das camadas  

#### Ferramenta de ajustes (uma ondinha):

- Seleciona imagem, converte em caminhos, ferramenta de ajustes: modifica parametros largura/força

#### Ferramenta mão livre:

- Curvas bezier, desenho livre    
- Nivel de suavização: quanto menor mais pontos terá a curva  
- Forma: area de transferencia: preenche forma fechada  
    
#### Caneta caligráfica:

- Largura, taxa de variação, angulo, estabilidade  
- Massa (muito legal) - deixa traço mais preciso  
    
#### Ferramenta spray:

- Cria um circulo, seleciona, ferramenta spray  
    - Modo 1: gera copias do elemento selecionado - cada 1 pode ser diferente  
    - Modo 2: mesma coisa porem todos sao iguais  
    - Modo 3: gera varias copias e tudo vira um unico objeto

#### Borracha:

- Modo que exlui objetos inteiros por onde passa  
- Modo que apaga partes dos objetos por onde passa

#### Balde de tinta:

- Modo cores visiveis - gera forma de contorno.  
- Preencher com intersecção.  
- Fechar intervalo - "tapa buracos".

#### Conta gotas:

- Seleciona objeto a colorir, botão conta gotas, clica no objeto colorido.  
- Se marcar item atribuir a opacidade - irá incluir também a opacidade.

#### Conector:

- Útil para trabalhar com gráficos.  
- Botão conector, seleciona um objeto e liga em outro objeto.  
- Opção de evitar objetos selecionados.

## Práticas

#### Criar pétalas de uma rosa:

    - Arraste o eixo de rotação de uma elipse para fora dela.  
    - Criar pétalas de rosas - muito legal.

#### Desenhar maçã:

    - Faz circulo, converte em caminho, achata polos (empurra), gradiente (hsl, remove alpha), duplica, pinta clone de branco,  
    - Usa gradiente (baixa hsl alpha), faz elipse preta buraco, faz talinho com caneta bezier, converte talo em caminho,  
    - Seleciona pontos do meio do talo, clica em suavizar

#### Colocar imagem em um texto (ou em uma forma):

    - Criar o texto (ou a forma) e importar uma imagem.  
    - Selecionar ambos, Objeto -\> Clip -\> Aplicar.

#### Recortar o fundo de uma imagem:

    - Importar imagem  
    - Com caneta bezier desenhar contornos da imagem  
    - Selecionar tudo, objeto - clip - aplicar 

#### Recortar parte de dentro da imagem:

    - Importa imagem  
    - Seleciona objeto - objeto - padrão de preenchimento - converter objeto em padrão  
    - Com caneta bezier desenhar contornos da imagem  
    - Selecinar tudo - caminho - diferença (ou exclusão)

#### Redimensionar página ao conteúdo:

    - Arquivo -\> Propriedades do desenho -\> Redimensionar página ao conteúdo

## Old

\#\# Como recortar o fundo de uma imagem:  
- importar imagem  
- com caneta bezier desenhar contornos da imagem  
- selecionar tudo, objeto - clip - aplicar 

\#\# Como recortar parte de dentro da imagem  
- importa imagem  
- seleciona objeto - objeto - padrão de preenchimento - converter objeto em padrão  
- com caneta bezier desenhar contornos da imagem  
- selecinar tudo - caminho - diferença (ou exclusão)

------------------------- Curso 1 - inkscape - Rnt Treinametnos -------------------------

Aula 1:   
- tecla numérica 5 \= ajusta zoom   
- canto direito inferior botão para alinhar objetos às bordas da página  
- ctrl \+ criar elipse \= alinhada  
- ctrl \+ redimensionar \= mantém a proporção  
- ctrl \+ d \= duplica um objeto  
- objeto -\> agrupar \== ctrl \+ g  
- shift \+ \== dar zoom ou z \+ click mouse  
- shift - \== menos zoom ou z \+ shift \+ click mouse  
- ctrl setas move tela  
- ctrl \+ scroll \== zoom in, zoom out

Aula 2:   
- arraste o eixo de rotação de uma elipse para fora dela  
- criar pétalas de rosas - muito legal

Aula 3:  
- page up - faz objeto subir   
- page down - faz objeto descer  
- pincel (topo) - preenchimento - edita cores e gradientes (seleciona linha no canto esquerdo inferior)  
- 2 clicks sobre a linha de gradiente - adiciona pontos sobre ela (cada ponto pode ter uma cor)  
- preenchimento e contorno - contorno - permite colocar ponta numa seta

Aula 4:  
- ferramenta de texto  
- ferramenta de gerenciador de camadas   
- travar uma camada - cadeado - não permite alterar a camada  
- quanto mais camadas mais organizado fica o projeto  
- \*ferramenta de gerar xml a partir do desenho  
- alinhar e distribuir - distribuir objetos de forma equidistante

Aula 5:  
- cria uma elipse com cor sólida, duplica ela, na segunda poe cor mais clara, gradiente radial, poe uma sobre a outra  
- poligono - seleciona o número de pontos - cria triangulos, ...  
- editor de nós, seleciona objeto, marca opção converter objeto selecionado em caminhos - modifica vérticies do objeto :D  
- modificando o vértice do objeto com o ctrl pressionado mantém a simetria  
- clica no primeiro, clica no que tu quer cortar, vai em caminho, diferença - corta o objeto  
- criação do olho - muito legal\! usou gradiente  
- seleciona objeto - espelhamento horizontal e vertical  
- duplica objeto, segura ctrl e move ele - deixa objeto alinhado  
- ferramenta lápis - suavização: traços mais limpos

Aula 6:  
- ferramenta editor de nós - cria um retangulo - converte objeto selecionado em caminhos - 2 clicks: cria nó  
- botao excluir nós selecionados  
- quebra caminho remove os nós   
- seleciona 2 vértices - botao unir nós selecionados - vira um triângulo      
- ferramenta ajustador  
- empurra regiões de caminho em qualquer direção - cria cavidades no objeto - bem legal  
- atrai caminhos - puxa bordas do desenho pra fora  
- desenhar maçã  
faz circulo, converte em caminho, achata polos (empurra), gradiente (hsl, remove alpha), duplica, pinta clone de branco,  
usa gradiente (baixa hsl alpha), faz elipse preta buraco, faz talinho com caneta bezier, converte talo em caminho,  
seleciona pontos do meio do talo, clica em suavizar

AQUIIIIIIIIIIIIIIIIIIIII  
    
Aula 7:  
- pétala de flor roxa com elipse modificada - gradientes e editor de nós (revisão)

Aula 8:  
- cria retangulo, seleciona com editor de nós, converter em caminho, converter contorno em caminho  
- arquivo, importar, seleciona imagem, caminho, rasterizar bitmap, por cores, seleciona objeto, desagrupar  
- caminho, união  
- caminho, diferença - apaga o objeto de cima e tudo o que ele sobrepor no de baixo  
- caminho, interseção - pega tudo que pertence ao mesmo tempo aos 2 objetos  
- caminho, exclusão - exclui tudo em comum  
- caminho, divisão - permite cortar um objeto - tirar uma fatia de uma pizza por exemplo  
- caminho, combinar - posso separar os objetos (unica diferença do uniao)

Aula 9:   
- objeto - propriedades do objeto - id, rótulo, título(ex.: cabeçalho, rodapé, adesivo), ocultar, bloquear  
- objeto - clip - permite remover fundo  
- objeto - mascara - mantem objeto anterior  
- cria retangulo - objeto - converter em guias - da pontos de referência para o objeto nao ficar torto  
- é melhor do que ir na régua e em puxar guia  
- objeto - exibir todos ou desbloquear todos    
- objeto - transformações - permite numericamente realizar transformações de movimento, escala, giro, inclinação em objetos  
- objeto - organizar - permite alinhar e distribuir de modo bem legal  
- camadas - modo de mistura - permite misturar cores das camadas  

Aula 10:   
- aba exibir   
- alternar entre 2 janelas do inkscape: ctrl \+ tab

Aula 11:  
- um mínion com o que foi aprendido

Aula 12:   
                
- continuação minion

Aula 13:  
- tirando dúvidas  
- cria um circulo, cria outro menor com uma parte por cima do primeiro, seleciona ambos, caminho - diferença  
- carva de bezier: bolinhas das pontas quanto mais longe do ponto central maior a curva  
- animalzinho roxo

Aula 14:  
- efeitos em textos   
- Aplicar gradiente em textos;  
- cria texto, seleciona, converter em caminhos  
- importar imagem, digita texto sobre ela, seleciona ambos, clip \=\> faz texto ter textura da imagem  
- permite botao direito, retirar recorte  
- digita texto, seleciona, filtros -\> aplicar diferentes filtros  
    
Aula 15:  
- Aula final: personagem completo

Aula 16:   
- Dúvidas:  
- Arquivo -\> Novo -\> Novo a partir de modelo - diversos modelos prontos (pdf, html5 etc)  
- - Arquivo -\> Importar ClipArt - baixa imagens vetorizadas da internet

------------------------- Curso 2 - inkscape - Rnt Treinametnos -------------------------

Aula 3:

https://www.youtube.com/watch?v=EdtoDll25WU\&list=PLFQlPs1NM\_-NnoLgubiszZ03JOerMmPwP\&index=3  
