# 🐍 Snake Game - Projeto em C

Bem-vindo ao projeto **Snake Game**! Este é um jogo clássico da cobrinha, desenvolvido em C, utilizando as bibliotecas SDL, Raylib e Emscripten. O jogo possui gráficos coloridos, sons e a mecânica clássica, onde o jogador controla a cobrinha e deve comer os itens que aparecem na tela sem bater nas bordas ou no próprio corpo.

## Tecnologias Utilizadas

- **SDL2**: Para renderização gráfica e manipulação de entrada de teclado.
- **Raylib**: Para facilitar o gerenciamento de gráficos e áudio.
- **Emscripten**: Para permitir a compilação do código para a web.
- **Git Submodules**: Utilizado para integrar repositórios externos como submódulos.

## Como Jogar

1. Compile o código fonte.
2. Execute o arquivo compilado.
3. Use as teclas de direção (cima, baixo, esquerda, direita) para mover a cobrinha.
4. O objetivo é comer o maior número possível de itens sem bater nas bordas ou em si mesmo.
5. A cada item comido, a cobrinha cresce.

## Instalação

### Requisitos

- **Git**: Para clonar o repositório e gerenciar as dependências.
- **Make**: Para compilar o projeto.
- **SDL2**: Certifique-se de ter o SDL2 instalado no seu sistema. Você pode instalar o SDL2 através do gerenciador de pacotes da sua distribuição (no caso do Linux) ou manualmente.
- **Raylib**: Também é necessário ter a Raylib configurada no seu ambiente de desenvolvimento.
- **Emscripten**: Para compilar para a web (opcional).

### Passo a Passo para Instalar e Rodar

#### 1. Clonar o Repositório

```bash
git clone --recurse-submodules https://github.com/myElonChaves565/projeto-snake-game-pt-br.git
cd projeto-snake-game-pt-br
