# ICG
### _Aluno_: Cristhyan de Araujo Cruz,_Matrícula_: 20180081817
### _Aluna_: Nayara Xavier de Melo Alves, _Matrícula_: 2016159064

A primeira atividade do curso, teve como objetivo verificar se o ambiente de desenvolvimento em OpenGL 3.3 está corretamente configurado nos computadores dos alunos e  Familizarizar os alunos com a estrutura de um programa OpenGL moderno.

inicialmente para a realização deste trabalho, foi feito download do programa OpenGL disponível no [repositório da disciplina](https://github.com/capagot/icg/tree/master/01_hello_world_gl/modern_opengl) logo após o download foi feito os seguintes passos:

### Passo 1:

Foi tentado a execução usando o sistema operacional windows 10, mas não obtive resultados positivos, sendo assim foi feito dual boot na máquina e instalado o sistema operacional UBUNTU na versão 19 LTS onde também não obtive resultado e por indicação de amigos que estão cursando a disciplina foi instalado a versão 20.04 LTS onde obtive êxito. Infelismente, não tirei print dessas ações.

### Passo 2:

Com a versão Linux UBUNTU 20.04 LTS instalada, foi possível instalar os pacotes exigidos, que foram:

sudo apt-get install freeglut3

sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev

sudo apt-get install libglew1.5-dev libglm-dev

### Passo 3:

Foi aberto o terminal na página da disciplina e e compilado o código para gerar o executável:

gcc main.c -o main.exe -lglut -lGL -lGLU -lm

![Print-1](https://github.com/Cristhyan-Cruz/ICG/blob/main/print00.png)

### Passo 4:

executando o programa:

./main.exe

![Print-2](https://github.com/Cristhyan-Cruz/ICG/blob/main/print01.png)

Conforme a figura acima, foi relatado um erro durante a execução do programa, sendo assim o programa foi compilado como mostra o print abaixo no Passo 5.

### Passo 5:

Foi usado o seguinte programa para a execução do programa: --

MESA_GL_VERSION_OVERRIDE=3.3 MESA_GLSL_VERSION_OVERRIDE=330 ./main.exe

![](https://github.com/Cristhyan-Cruz/ICG/blob/main/print02.png)

Sendo assim, o trabalho foi concluido com êxito!

## Referências

[https://github.com/capagot/icg](https://github.com/capagot/icg)

[http://www.codebind.com/linux-tutorials/install-opengl-ubuntu-linux/](http://www.codebind.com/linux-tutorials/install-opengl-ubuntu-linux/)

[https://learnopengl.com/](https://learnopengl.com/)







