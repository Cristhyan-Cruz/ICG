### Aluno: Cristhyan de Araújo Cruz,  Matrícula: 20180081817
### Aluno: Nayara Xavier de Melo,     Matricula: 2016159064

## Pipeline Gráfico

O trabalho tem como  objetivo familiarizar os alunos com a estrutura do pipline gráfico através da implementação das transformações geométricas que o compõem. Esta implementação será feita com auxílio da biblioteca glme sua execução ocorrerá nos shaders do OpenGL.

Inicialmente foi instalada a biblioteca **GLEW** através do comando: **_sudo apt-get install libglew-dev_**, depois foi feito o clone do projeto, onde a biblioteca **glm** foi instalada automaticamente através do comando: **_$ git clone --recurse-submodules https://github.com/capagot/icg.git_** . Tendo as dependências instaladas, foram realizadas alterações nas matrizes _'model, 'view' e 'projection'_ de forma a gerar as imagens solicitadas na descrição do projeto. 

### 1-Escala

Foi modificada a Matriz _Model_ e gerou os seguintes resultados:

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/escala.png)
![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/escala1.png)

### 2-Translação

Foi modificada a Matriz _Model_ e gerou os seguintes resultados:

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/transla%C3%A7%C3%A3o.png)
![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/transla%C3%A7%C3%A3o1.png)

### 3-Projeção Perspectiva

Foi modificada a Matriz _Projection_ e gerou os seguintes resultados:

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/proje%C3%A7%C3%A3o.png)
![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/proje%C3%A7%C3%A3o1.png)

### 4-Posição da Câmera

Após todos os cálculos, chegamos na seguinte solução: 

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/c%C3%A2mera.png)
![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/c%C3%A2mera1.png)

### 5-Transformações Livres

Para a Transformação Livre, inicialmente mudou-se o _Array_ contendo as coordenadas X,Y e Z de três Vértices. 

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/livre.png)

Chegando ao seguinte resultado:

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/livre1.png)

Logo após foram feitas alterações na matrizes _model_ e _view_

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/livre2.png)

Gerando o seguinte resultado Final:

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/Trabalho_03/livre3.png)

### Referências

[https://github.com/capagot/icg/tree/master/03_transformations](https://github.com/capagot/icg/tree/master/03_transformations)

[https://glm.g-truc.net/0.9.9/index.html](https://glm.g-truc.net/0.9.9/index.html)

[http://glew.sourceforge.net/](http://glew.sourceforge.net/)

[https://glad.dav1d.de/](https://glad.dav1d.de/)

[http://www.opengl-tutorial.org/](http://www.opengl-tutorial.org/)

[http://www.opengl-tutorial.org/beginners-tutorials/tutorial-3-matrices](http://www.opengl-tutorial.org/beginners-tutorials/tutorial-3-matrices)







