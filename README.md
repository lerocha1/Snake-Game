# Snake-Game
Snake Game - Famoso Jogo da cobrinha em python.

Este código gera um Snake Game simples usando a biblioteca Pygame em Python. A janela do jogo tem largura de 800 pixels e altura de 600 pixels. A cobra é representada por uma série de retângulos, e o objetivo é controlar a cobra para comer e crescer mais. O jogo termina se a cobra colidir com as paredes ou com o próprio corpo.

O loop do jogo verifica continuamente a entrada do usuário e atualiza a posição da cobra de acordo. O movimento da cobra é controlado com as setas do teclado. A cabeça da cobra é representada por um retângulo e seu corpo é armazenado em uma lista. O comprimento da cobra aumenta quando ela come, e o jogo termina se a cobra colidir consigo mesma ou com as paredes.

A tela de fim de jogo é exibida quando o jogo termina, mostrando a pontuação do jogador e dando-lhe a opção de desistir ou jogar novamente. A pontuação é exibida no canto superior esquerdo da janela do jogo.

Para rodar o jogo, você precisa ter a biblioteca Pygame instalada. Você pode instalá-lo usando o seguinte comando: pip install pygame

Recomendo fortemente criar o diretorio e dento dele no bash, utilizando sua IDE use os seguinte comandos:

python -m venv myvenv   (myvenv é o nome da sua venv eu utilizei venv_game)
Após cria - lá navegue usando os comandos "cd myvenv\Scripts ==> ja dentro da pasta scripts rode activate. Caso de erro, é porque o seu powerShell esta com set policy para nao rodar scripts. 

Então rode o comando abaixo e volte ao passo de ativar a venv

no modo administrador no powershell - Set-ExecutionPolicy Unrestricted


- Ícone de Coração: <i class="fas fa-heart"></i>
- Ícone de Estrela: <i class="fas fa-star"></i>
