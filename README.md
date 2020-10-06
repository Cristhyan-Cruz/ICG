# ICG
Trabalhos da Disciplina Introdução a Computação Gráfica ministrada no período 2020.1

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

Foi aberto o terminal na página da disciplina e e compilado o código:

gcc main.c -o main.exe -lglut -lGL -lGLU -lm

### Passo 4:

executado o programa:

./main.exe
