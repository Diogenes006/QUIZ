# 🧠 Quiz Interativo - Desenvolvimento Web

Este é um projeto de **Quiz Interativo** feito com **HTML5**, **CSS3** e **JavaScript**, ideal para iniciantes praticarem conceitos de desenvolvimento web e manipulação da DOM.

---

## 🎯 Funcionalidades

- ✅ Interface responsiva (funciona em 1920x1080 e 430x932)
- ✅ 5 perguntas aleatórias por jogo
- ✅ Dois tipos de perguntas:
  - 🔘 Múltipla escolha (até 5 opções)
  - ⚖️ Tela dividida (duas opções)
- ✅ Respostas embaralhadas automaticamente
- ✅ Resultado final exibido em um modal
- ✅ Som reproduzido se o desempenho for maior que 50%

---

## 💻 Tecnologias Usadas

- HTML5
- CSS3
- JavaScript (DOM API)

---

## ▶️ Como Executar

1. Clone ou baixe este repositório
2. Abra a pasta do projeto no **Visual Studio Code**
3. No VS Code:
   - Se tiver o plugin **Live Server**, clique com o botão direito no `index.html` e selecione `Abrir com Live Server`
   - Ou, simplesmente, **abra o arquivo `index.html` no navegador** com dois cliques

---

## 🖼️ Como Personalizar o Fundo

Se quiser mudar o fundo para uma **imagem personalizada**, basta substituir o estilo do `body` no CSS assim:

```css
body {
  background: url('fundo.jpg') no-repeat center center fixed;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  padding: 20px;
}



