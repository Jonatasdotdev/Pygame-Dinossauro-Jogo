# Jogo do Dinossauro

Este é um jogo simples inspirado no popular jogo do dinossauro que aparece no navegador Google Chrome quando não há conexão com a internet. O jogo foi desenvolvido em Python usando a biblioteca Pygame.

## Estrutura do Projeto

O projeto inclui um jogo básico onde um dinossauro deve desviar de obstáculos e colecionar pontos. O jogo é executado em uma janela Pygame e inclui as seguintes funcionalidades:

- Movimento do dinossauro (correr, pular e agachar).
- Obstáculos variados (cactos pequenos e grandes, pássaros).
- Pontuação e velocidade do jogo aumentam conforme o progresso.
- Tela de menu para iniciar ou reiniciar o jogo após a morte.

## Funcionalidades

- **Dinossauro**: O dinossauro pode correr, pular e agachar. Cada ação é representada por imagens diferentes.
- **Obstáculos**: O jogo inclui cactos e pássaros que o dinossauro deve evitar.
- **Pontuação**: A pontuação aumenta com o tempo e a velocidade do jogo aumenta.
- **Tela de Menu**: Permite ao jogador iniciar ou reiniciar o jogo após a morte.

## Requisitos

- **Python**: Certifique-se de que o Python está instalado em sua máquina.
- **Pygame**: Este projeto usa a biblioteca Pygame. Instale-a usando:

  ```bash
  pip install pygame
  ```

## Como Executar

1. **Clone o Repositório**

   ```bash
   git clone <URL_DO_REPOSITÓRIO>
   cd <NOME_DO_REPOSITÓRIO>
   ```

2. **Prepare os Recursos**

   Certifique-se de que as imagens do dinossauro e obstáculos estão localizadas na pasta `Assets`. A estrutura do diretório deve ser:

   ```
   Assets/
     Dino/
       DinoRun1.png
       DinoRun2.png
       DinoJump.png
       DinoDuck1.png
       DinoDuck2.png
     Cactus/
       SmallCactus1.png
       SmallCactus2.png
       SmallCactus3.png
       LargeCactus1.png
       LargeCactus2.png
       LargeCactus3.png
     Bird/
       Bird1.png
       Bird2.png
     Other/
       Cloud.png
       Track.png
   ```

3. **Execute o Jogo**

   Para iniciar o jogo, execute o seguinte comando:

   ```bash
   python <NOME_DO_ARQUIVO>.py
   ```

## Problemas Conhecidos

- **Bug no Agachar**: Há um bug conhecido onde a tecla de agachar não funciona corretamente em algumas situações. Isso precisa de correção.
- **Música**: A funcionalidade de adicionar música ao jogo ainda não foi implementada e está planejada para futuras versões.

## Contribuições

Se você deseja contribuir para o projeto, considere as seguintes áreas:

- **Correção de Bugs**: Contribua com correções para o bug de agachar.
- **Adição de Música**: Implemente a funcionalidade para tocar música durante o jogo.
- **Outras Melhoria**: Sinta-se à vontade para sugerir ou adicionar novas funcionalidades.
- **Creditos pro canal**: https://www.youtube.com/@MaxOnTech

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).



