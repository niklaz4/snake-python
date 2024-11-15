# Jogo da Cobrinha em Pygame

Este é um simples jogo da cobrinha (Snake Game) criado usando o módulo `pygame` em Python. O objetivo do jogo é controlar a cobra para capturar o alvo (representado em vermelho) que aparece em posições aleatórias na tela. Cada vez que a cobra captura o alvo, seu comprimento aumenta. Se a cobra sair dos limites da tela, o jogo é reiniciado.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal utilizada.
- **Pygame**: Biblioteca para desenvolvimento de jogos 2D em Python, usada para renderização de gráficos, detecção de eventos e controle de elementos na tela.

## Como Executar o Código

1. **Pré-requisitos**:
   - Python 3 instalado.
   - Biblioteca Pygame instalada. Caso não tenha o Pygame, instale com o comando:
     ```bash
     pip install pygame
     ```

2. **Executando o Jogo**:
   - Salve o código em um arquivo com extensão `.py`, por exemplo `snake_game.py`.
   - Abra um terminal na pasta onde o arquivo foi salvo e execute o comando:
     ```bash
     python snake_game.py
     ```

3. **Controles do Jogo**:
   - **W**: Move a cobra para cima.
   - **S**: Move a cobra para baixo.
   - **A**: Move a cobra para a esquerda.
   - **D**: Move a cobra para a direita.
   - O objetivo é capturar o alvo vermelho e crescer a cobra. Caso a cobra saia da área de jogo, ela será reiniciada para o tamanho inicial.

4. **Encerrando o Jogo**:
   - Para encerrar o jogo, feche a janela ou pressione o botão de fechar (X) na janela do jogo.

## Estrutura do Código

- **Funções Principais**:
  - `generate_starting_position()`: Gera uma posição inicial aleatória para o alvo e a cobra.
  - `reset()`: Redefine a posição da cobra e do alvo quando necessário.
  - `is_out_of_bounds()`: Verifica se a cobra está fora dos limites da tela.

- **Loop Principal**:
  - Lida com eventos de teclado e controle do movimento da cobra.
  - Atualiza a posição da cobra e do alvo, gerenciando o crescimento e as condições de reinício.
  - Renderiza a cobra e o alvo na tela e atualiza a interface do jogo.

## Contribuições

Contribuições e sugestões para melhorias no código são bem-vindas. Sinta-se à vontade para fazer um fork do repositório, realizar alterações e submeter um Pull Request.

---

**Divirta-se jogando!**
