### Aluno: Cristhyan de Araujo Cruz, Matricula: 20180081817

### Aluno: Nayara Xavier de Melo, Matricula: 2016159064

## Atividade

No segundo trabalho da disciplina foi implementado um algoritmos para a rasterização de pontos e linhas. Os triângulos foram desenhados através da rasterização das linhas que compõem suas arestas. A rasterização destas primitivas foram feitas simulando o acesso direto a memória de vídeo.Como os sistemas operacionais atuais protegem a memória quanto ao acesso direto, foi utilizado um frameworkonde seus arquivos podem ser acessados no [repositório](https://github.com/capagot/icg/tree/master/02_mygl_framework), fornecido pelo professor, que simula o acesso à memória de vídeo.
 
 Os arquivos mygl.h e mygl.c são os únicos arquivos que foram alterados durante a realização desta atividade.O arquivo mygl.h contém a declaração das funções responsaveis por invocar as funções de rasterização e o arquivo mygl.c é o lugar onde serão definidas as funções de rasterização.
 
 ## Função PutPixel
 
 Esta função Rasteriza um ponto na memória de vídeo recebendo como parâmetros as coordenadas (x,y) do pixel na tela e sua cor (RGBA).  
 
 ## Função DrawLine
 
 Esta função rasteriza uma linha na tela, recebendo como parâmetros as coordenadas dos seus vértices inicial e final (representados respectivamente pelas tuplas (x0,y0) e (x1,y1)) e ascores (no formato RGBA) de cada vértice. As cores dos  pixels ao longo da linha rasterizadadevem  ser obtidas  por meio de  interpolação linear  das  cores  dos  vértices.  O algoritmo  de rasterização de linha implementado foi o Algoritmo do Ponto Médio!
 
 ## Função DrawTriangle
 
Esta função desenha as arestas de um triângulo na tela, recebendo comoparâmetros as posições dos três vértices (x0,y0), (x1,y1) e (x2,y2) bem como as cores (RGBA)de cada um dos vértices. As cores dos pixels das arestas do triângulo foram obtidas através da  interpolação linear das cores de seus vértices. 

## Discussões 

O trabalho teve uma certa complexidade na implementação do algoritmo do ponto médio por conta dos sinais, mas na video aula o professor aprensenta o algoritmo do ponto ponto medio para o primeiro octante, onde foi possivel prosseguir para a conclusão do trabalho.

## Referências

[https://github.com/capagot/icg](https://github.com/capagot/icg)

[https://learnopengl.com/](https://learnopengl.com/)

[https://sig-arq.ufpb.br/arquivos/20200681159dc7252456573592019b615/trabalho_2.pdf](https://sig-arq.ufpb.br/arquivos/20200681159dc7252456573592019b615/trabalho_2.pdf)
