# Jogo da Cobra (Snake)

Este projeto é uma implementação básica do jogo da cobra (Snake) usando Python e a biblioteca Tkinter para a interface gráfica. O jogo é jogado em uma tela onde a cobra se move e coleta maçãs para aumentar a pontuação.

## Descrição

O jogo apresenta os seguintes recursos:
- A cobra é composta por segmentos que se movem em uma tela preta.
- Maçãs aparecem aleatoriamente na tela, e cada maçã coletada aumenta a pontuação e o comprimento da cobra.
- A cobra e o jogador perdem o jogo ao colidir com as bordas da tela ou com ela mesma.

## Funcionalidades

- **Controle da Cobra**: Use as teclas de seta do teclado para controlar a direção da cobra.
- **Pontuação**: A pontuação é atualizada sempre que a cobra coleta uma maçã.
- **Colisões**: O jogo termina se a cobra colidir com as bordas da tela ou com ela mesma.
- **Tela de Game Over**: Mostra a pontuação final quando o jogo termina.

## Requisitos

- Python 3.x
- Biblioteca Tkinter (incluída na maioria das instalações padrão do Python)

## Executando o Jogo

1. **Certifique-se de ter Python 3.x instalado**.

2. **Salve o código fornecido em um arquivo chamado `snake.py`**.

3. **Abra um terminal ou prompt de comando**.

4. **Navegue até o diretório onde você salvou o arquivo**.

5. **Execute o comando**:

    ```bash
    python snake.py
    ```

6. **O jogo será iniciado em uma janela Tkinter**. Use as teclas de seta para controlar a cobra.

## Estrutura do Código

- **`Cons`**: Contém constantes usadas em todo o jogo, como dimensões da tela e tamanhos dos objetos.
- **`Board`**: Gerencia a lógica do jogo, incluindo criação de objetos, movimentação da cobra, colisões e pontuação.
- **`Snake`**: Cria a janela principal e inicializa o jogo.
- **`main`**: Função principal que inicializa e executa o jogo.

## Observações

- **Ajustes**: Você pode modificar as constantes na classe `Cons` para alterar as dimensões da tela, a velocidade do jogo e o tamanho da cobra.
- **Extensões**: Considere adicionar novos recursos como níveis, diferentes tipos de alimentos ou modos de dificuldade.

## Contribuições

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades. Abra um issue ou um pull request no repositório.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Para mais informações, entre em contato com [Paulo Cezar](mailto:seuemail@dominio.com).
