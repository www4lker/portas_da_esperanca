# portas_da_esperanca

![Logo](https://i.postimg.cc/KvRDT60C/image.png)
[Earth, Wind & Fire - In the Stone (Audio)](https://www.youtube.com/watch?v=6Z2xClustQo)

Joguinho educacional baseado no problema Monty Hall, mais conhecido como Portas da Esperança no Brasil

## O jogo

O problema de Monty Hall é um quebra-cabeça de probabilidade do game show "Let's Make a Deal". No quebra-cabeça, um participante escolhe uma das três portas para ganhar um prêmio. Depois que o participante escolhe, o apresentador, Monty Hall, abre uma das portas restantes para revelar que ela não contém o prêmio. O participante tem então a opção de *manter sua escolha original ou mudar para a outra porta fechada*. Surpreendentemente, a troca de portas aumenta as chances de vitória do participante.

Para entender melhor o problema, sugere-se modelá-lo usando a programação Python. Assim, aplicam-se dois cenários: um em que o participante não troca de porta e outro em que ele troca. Usando geradores de números aleatórios, demonstra-se a probabilidade de vitória em cada cenário.Finalmente, fica claro que quando o participante mantém sua escolha original, suas chances de ganhar permanecem em um terço. Entretanto, se ele trocar de porta, suas chances aumentam para dois terços.

Enfatiza-se que a execução de um grande número de testes, como 1.000, revela o verdadeiro impacto da troca de portas. Os resultados mostram que, com a troca de portas, os participantes ganham cerca de dois terços das vezes, o que é consistente com a solução teórica. Reconhece-se que esse resultado contraintuitivo pode ser difícil de entender, mas pode ser explicado pelo fato de que a revelação de Monty oferece uma oportunidade extra de troca, aumentando as chances.

Conclui-se que, para explicar, jogar o jogo apenas uma vez não permite que o participante observe a vantagem de trocar de porta. Entretanto, com mais tentativas, a *lei dos grandes números* entra em ação, garantindo que os resultados se aproximem do valor esperado. Esse conceito se aplica a outras situações baseadas no acaso, como os jogos de cassino, em que a vantagem da casa se torna aparente com um grande número de jogos.

Fonte: [Artigo Wired](https://www.wired.com/story/monty-hall-problem-python/)


## Como jogar

1. Execute o script `main.py` usando Python.
2. A janela principal do jogo será exibida com três botões que representam as portas.
3. Clique em um dos botões de porta para fazer sua escolha inicial.
4. Monty abrirá uma das outras portas que não tem o prêmio.
5. Aparecerá uma janela de diálogo perguntando se você deseja alterar sua escolha.
6. Clique em "Sim" (Yes) para mudar sua escolha ou em "Não" (No) para manter sua escolha original.
7. O resultado final será exibido, indicando se você ganhou o prêmio ou não.
8. Você pode clicar em "Jogar Novamente" para reiniciar o jogo e jogar outra rodada.
9. Clique em "Aprenda mais" (Learn More) para ler uma explicação do problema de Monty Hall.
10. Após 10 rodadas, as estatísticas serão exibidas, mostrando as porcentagens de vitória com e sem troca.

## Dependências

- Python 3.x
- Tkinter (normalmente incluído nas instalações do Python)

## Primeiros passos

1. Clone este repositório:

   ```bash
   git clone https://github.com/your-username/monty-hall-game.git



## ENGLISH VERSION


# Monty Hall Game

This is a simple implementation of the Monty Hall game using Python and Tkinter.

## Description

The Monty Hall problem is a probability puzzle that demonstrates the importance of updating probabilities when receiving new information. The game involves three doors, behind one of which is a prize, and behind the other two, there is nothing.

After choosing a door, Monty Hall (also known as Esperança) who knows what is behind each door, opens one of the other two doors that does not have the prize. Then, you have the option to either stick with your original choice or switch to the other remaining closed door.

The counterintuitive idea is that switching doors increases your chances of winning. Initially, your chance of choosing the correct door is 1/3, and there is a 2/3 chance that the prize is behind the other two doors. When Monty opens a door without the prize, the probability of 2/3 still applies to the other doors. So, switching your choice increases your chances of winning to 2/3, while sticking with your original choice only has a 1/3 chance.

sOURCE: Fonte: [Wired ARTICLE](https://www.wired.com/story/monty-hall-problem-python/)

## How to Play

1. Run the `main.py` script using Python.
2. The main game window will appear with three buttons representing the doors.
3. Click on one of the door buttons to make your initial choice.
4. Monty will open one of the other doors that does not have the prize.
5. A dialog window will appear asking if you want to change your choice.
6. Click "Sim" (Yes) to switch your choice or "Não" (No) to stick with your original choice.
7. The final result will be shown, indicating if you won the prize or not.
8. You can click "Jogar Novamente" (Play Again) to reset the game and play another round.
9. Click "Aprenda mais" (Learn More) to read an explanation of the Monty Hall problem.
10. After 10 rounds, the statistics will be displayed, showing the win percentages with and without switching.

## Dependencies

- Python 3.x
- Tkinter (usually included with Python installations)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/monty-hall-game.git
