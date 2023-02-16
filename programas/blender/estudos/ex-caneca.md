# Blender - Criar uma caneca

- apague o cubo, a camera e a fonte de luz
- crie um cilindro: add -> mesh -> cylinder
- opções add cylinder (canto esq inferior): vértices: 10, radius: 1m, deph: 3m
- menu overlay (canto dir sup): ativar wireframe (linhas de construção)
- entrar nas opções de edição: seleciona objeto + TAB ou menu object mode (canto sup esq) -> edit mode
- ao lado de "edit mode" há 3 opções: pontos, linhas, faces -> clique em faces usando a ferramenta de seleção ou pressione 3
- selecione o topo do cilindro, bt dir mouse -> opcao: inset faces
- selecione o topo do cilindro (parte interna), bt dir mouse -> opcao: extrude faces
- criar linhas de corte: ferramenta de Loop cut -> criar 4 linhas de corte, ferramenta de selecao e clica fora
- seleciona 2 quadrados da lateral -> btdir -> inset faces, btdir -> extrude
- seleciona 2 pontos da alça, diminui distancia - gera "planos inclinados"
- seleciona 2 planos inclinados, btdir -> bridge faces (number of cuts = 1)
- seleciona linha do meio da alça, select -> select loops -> edge loops, mover para diminuir abertura alça.
