# Comparação dos métodos DFS, BFS, BFS-Euclidiano e BFS-Manhattan 

<div style="display: inline-block;">
<img align="center" height="20px" width="60px" src="https://img.shields.io/badge/Language-C-blue"/> 
<img align="center" height="20px" width="80px" src="https://img.shields.io/badge/Made%20in-VSCode-red"/> 
</div>
<br>
<p align="justify">
  Dois métodos comuns para resolver labirintos são o DFS, mais sobre ele <a href="https://github.com/Kingdrasill/labyrinth-dfs">https://github.com/Kingdrasill/labyrinth-dfs</a>, e o BFS, mais sobre ele <a href="https://github.com/Kingdrasill/labyrinth-bfs">https://github.com/Kingdrasill/labyrinth-bfs</a>. Os dois métodos resolvem um labirinto o que utilizaremos para medir qual é o melhor são os números de iterações de cada método, uma iteração é uma inserção na estrutura que a armazena o caminho percorrido. Tem como ainda melhorar o método BFS que é na hora que for andar escolher o caminho em que que a distância do final seja a menor, está distância por ser calculada por heuristíca euclidiana ou manhattan. A formúla do cálculo das mesma por ser visto na imagem a seguir:
</p>
<p align="center">
  <img src="imgs/formulas.png">
</p>

<p align="justify">
  O objetivo deste algoritmo é dar o usuário a escolha de qual método usar em labirinto, passdo pelo mesmo em um arquivo de texto, e o deixar ver a diferença dos números de iterações de cada método. Além de mostrar qual o melhor método por meio estátisco, os testes foram feitos com 30 labirintos 9x9 e 13x13 diferentes em que 10 foram em labirintos normais, 10 com mais bloqueios e 10 com menos bloqueios. Todos os labirintos de teste estão na pasta teste, embaixo de cada labirinto tem o número de iterações de cada metódo. 
<p>

> Observação: Em alguns labirintos o método do DFS não consegue terminar o labirinto, isto acontece por causa de como o método foi feito. O método não consegue andar para cima, então metodos que necisstam de andar para cima para terminar o labirinto o método não consegue proguedir mais e termina. Na pasta teste os labirintos em que o DFS não termina vai estar o número de iterações até para com um asterisco(X*).  
  
# Labirintos 9x9
  
# LAbirintos 13x13

# Compilação e Execução

O algoritmo possui um arquivo Makefile que realiza todo o procedimento de compilação e execução. Para tanto, temos as seguintes diretrizes de execução:


| Comando                |  Função                                                                                           |                     
| -----------------------| ------------------------------------------------------------------------------------------------- |
|  `make clean`          | Apaga a última compilação realizada contida na pasta build                                        |
|  `make`                | Executa a compilação do programa utilizando o gcc, e o resultado vai para a pasta build           |
|  `make run`            | Executa o programa da pasta build após a realização da compilação                                 |


<p>Trabalho realizado Gabriel Teixeira Júlio e Lívia Gonçalves - Maio/2022</p>
