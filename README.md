# 🎯 Jogo do Número Secreto

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Um jogo interativo onde o objetivo é adivinhar um número secreto gerado aleatoriamente entre 1 e 50.

## 🕹️ Como Jogar

1. O jogo sorteia um número secreto entre **1 e 50**
2. Digite seu palpite no campo de entrada
3. Clique em **"Chutar"** para confirmar
4. O jogo indica se o número secreto é **maior** ou **menor** que o seu chute
5. Continue tentando até acertar!
6. Ao acertar, o número de tentativas é exibido na tela
7. Clique em **"Reiniciar"** para jogar novamente

## ✨ Funcionalidades

- 🔢 Geração de números aleatórios sem repetição — o mesmo número não é sorteado duas vezes seguidas até que todos os números do intervalo sejam usados
- 🔊 Feedback por voz usando **ResponsiveVoice** (voz feminina em Português Brasileiro)
- 💬 Dicas em tempo real indicando se o número secreto é maior ou menor
- 🔄 Botão de reinício que só é habilitado após o jogador acertar
- 📱 Interface simples e responsiva

## 🗂️ Estrutura do Projeto

```
📦 numero-secreto/
├── index.html
├── style.css
└── app.js
```

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da página |
| CSS3 | Estilização e layout |
| JavaScript | Lógica do jogo |
| ResponsiveVoice | Síntese de voz em PT-BR |

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/numero-secreto.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd numero-secreto
   ```

3. Abra o arquivo `index.html` no seu navegador — sem necessidade de servidor ou instalação!

## 🧠 Lógica Principal

- **Geração sem repetição:** o jogo mantém uma lista dos números já sorteados. Quando todos os números do intervalo (1–50) forem utilizados, a lista é resetada e o ciclo recomeça.
- **Contagem de tentativas:** a cada chute errado o contador incrementa, e ao acertar o jogo exibe o total com a palavra corretamente flexionada ("tentativa" ou "tentativas").
- **Acessibilidade por voz:** cada mensagem exibida na tela também é lida em voz alta via ResponsiveVoice.

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---
