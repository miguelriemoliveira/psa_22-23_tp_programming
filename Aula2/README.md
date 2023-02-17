## Aula 2 - Visualização em Matlab

Tópicos a abordar:

Visualização em Matlab

- Desenho de pontos
- Desenho de linhas
- Cores e marcadores
- Desenho de polígonos
- Mapas de cor
- Animações com sobreposição do desenho
- Animações com alteração das propriedades do gráfico

### Exercício 2.1

Desenhe 100 pontos aleatoriamente gerados entre $x \in [-10,10], y \in [-5,5]$.

### Exercício 2.2

Escolha aleatoriamente 10 pares de pontos de entre os gerados no exercício anterior, e  desenhe um segmento de reta para cada par.

### Exercício 2.3

Desenhe um polígono dado pelos pontos definidos com a função _ginput_. A figura deve mostrar o contorno do triângulo a azul e o seu interior a cinzento.


### Exercício 2.4

Aplique a um ponto uma matriz de transformação geométrica a 2D, dada por:

$
\begin{bmatrix}
cos(\alpha) & sin(\alpha) & t_x \\
-sin(\alpha) & cos(\alpha) & t_y \\
0 & 0 & 1
\end{bmatrix}
$

O ponto deverá estar definido em coordenadas homogéneas, i.e.:

$\begin{bmatrix}
x \\
y \\
1
\end{bmatrix}$

Desenhe o ponto a mover-se pelo cenário aplicando matrizes de transformação com sucessivos valores de $\alpha$, $t_x$ e $t_y$