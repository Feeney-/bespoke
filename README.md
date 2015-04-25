Bespoke
=====

Bespoke transforma uma imagem normal numa composição que remete para o cubismo.

Tropecei uma imagem curiosa de azulejos triangulares que foram, aparentemente, colocados de forma aleatórica e, no entanto, pareciam ser unificadas e ter ritmo. Como é que isso funciona?
Depois aprendi acerta da triangulação Delaunay. Fascinado pelo algoritmo e pela sua qualidade estética, rapidamente experimentei no Processing. O mosaico resultante fazia me lembrar quadros do Cubismo Órfico, com cores expressivas e mosaicos com ritmo, embora se calhar um bocado mais mecânico. Eu chamei de Bespoke.

Agora o estilo mosaico ficou mais popular outra vez, e com d3.js, fazendo os triângulos Delaunay tão simples quanto chamar uma função.

Composição
===

Mosaicos Delaunay são baseados num conjunto de pontos. À medida que os pontos mexem, a imagem resultante muda. Como colocar estes pontos? Há 4 estudos:
1. Pontos que são colocados de forma aleatória
2. Pontos escolhidos usando o algoritmo de melhor candidato
3. Deteção de pontos chaves usados na imagem original usando a biblioteca JSFeat
4.Mexendo manualmente os pontos

Cores
===
Ao mapear a posição dos pontos para pixéis da imagem original, podemos extrair a cor e aplica-la para pintar os nossos triângulos. Por exemplo, podemos tirar a cor do centro do triangulo, ou uma cor média dos três pontos do triangulo, ou um gradiente com múltiplas paragens baseadas na interpolação de pontos uma linha bissetora.

Abstração
===
Mais triângulos dão a imagem mais detalhe, embora fazendo-a mais apática também. Gradientes adicionam ornamentos e suavizam a imagem, enquanto cores sólidas sentes mais diretas e confiantes. Adicionar elementos gráficos auxiliares, tal como círculos e contornos, achata a imagem e fazem um render gráfico. Um dos aspectos mais fascinantes da arte digital é o jogo entre imaginação e algoritmos, a surpresa derivada de ajustar ideias e refinar o código. Encorajo a experimentar Bespoke, tal como buscar o código fonte e pôr as forças imaginativas ao trabalho.
Bespoke5.jpeg

Documentação
=====

Pode ser visto em funcionamento aqui: 

http://bespoke.pt.vu

Faz download, vê os ficheiros e altera a gosto

