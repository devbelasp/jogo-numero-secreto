# 🎯 Jogo do Número Secreto

Um pequeno jogo interativo feito em HTML, CSS e JavaScript onde o jogador precisa adivinhar qual é o número secreto sorteado pelo sistema.

## 💡 Como funciona?

- O jogo escolhe aleatoriamente um número entre 1 e 10.
- O usuário digita um número e recebe uma dica se o número secreto é maior ou menor.
- Quando acerta, o jogo mostra quantas tentativas foram necessárias.
- Há um botão para reiniciar o jogo com um novo número aleatório.

## 🛠️ Funcionalidades implementadas

- Geração de número aleatório com `Math.random()`.
- Controle de tentativas.
- Prevenção de repetição de números já sorteados.
- Exibição dinâmica de mensagens na tela com `innerHTML`.
- Uso de **funções reutilizáveis** para:
  - Exibir mensagens.
  - Gerar número aleatório.
  - Limpar campo de entrada.
  - Reiniciar o jogo.
- Uso da **API de voz do navegador (Web Speech API)** para leitura automática das mensagens.

## 📚 O que foi aprendido

Durante o desenvolvimento, foram praticados os seguintes conceitos:

- **Manipulação do DOM** com `document.querySelector()` e `innerHTML`.
- **Criação e reutilização de funções** JavaScript.
- **Geração de números aleatórios** com `Math.random()` e `parseInt()`.
- **Listas (arrays)** para armazenar números já sorteados e evitar repetições.
- **Condicionais (if/else)** e **operadores ternários**.
- **Incremento de variáveis** e controle de tentativas.
- **API de síntese de voz** (`speechSynthesis`) para acessibilidade.
- **Boas práticas com nomes de variáveis** e separação de responsabilidades.

## 🚀 Como rodar

1. Baixe ou clone o repositório.
2. Abra o arquivo `index.html` em um navegador moderno (recomenda-se Chrome).
3. Interaja com o jogo diretamente na página.

## 👩‍💻 Tecnologias usadas

- HTML5
- CSS3
- JavaScript
- Web Speech API

---

Feito com 💛 durante os estudos de lógica de programação - Alura.


