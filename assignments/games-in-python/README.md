# 📘 Atividade: Jogo da Forca em Python

## 🎯 Objetivo

Pratique strings, listas, laços de repetição, condicionais e entrada de dados ao criar um jogo da Forca no qual o jogador tenta adivinhar uma palavra secreta antes de ficar sem tentativas.

## 📝 Tarefas

### 🛠️ Implementar a lógica do jogo

#### Descrição
Prepare as palavras e os dados necessários para uma partida. Escolha uma palavra secreta aleatoriamente e acompanhe as letras descobertas e as tentativas incorretas.

#### Requisitos
O programa concluído deve:

- Escolher aleatoriamente uma palavra de uma lista predefinida.
- Exibir cada letra ainda não descoberta como `_`, mantendo visíveis as letras já acertadas.
- Registrar os palpites e descontar uma tentativa apenas quando o palpite estiver incorreto.
- Definir um limite de tentativas incorretas e acompanhar quantas restam.

### 🛠️ Criar o fluxo da partida

#### Descrição
Use um laço para conduzir a partida, receber palpites do jogador e atualizar a exibição até que ele vença ou fique sem tentativas.

#### Requisitos
O programa concluído deve:

- Solicitar ao jogador um palpite de letra a cada rodada.
- Informar o progresso da palavra e as tentativas incorretas restantes após cada palpite.
- Encerrar a partida quando todas as letras forem descobertas ou quando as tentativas acabarem.
- Exibir uma mensagem de vitória ou derrota; em caso de derrota, revelar a palavra secreta.
