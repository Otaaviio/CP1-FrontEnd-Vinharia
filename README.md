# 🍷 **Vinharia Agnello**

## 📖 **Sobre a Vinheria Agnello**

A **Vinheria Agnello** foi fundada há mais de 15 anos em São Paulo por Giulio, um apaixonado por vinhos e pelas tradições familiares. Desde o início, o negócio teve um forte caráter familiar, contando com o apoio de sua filha Bianca, que cresceu envolvida com a loja e mais tarde passou a atuar na gestão. Com apenas uma loja física, a vinheria se destacou pelo atendimento personalizado e pela consultoria especializada oferecida aos clientes.

Giulio sempre prezou por um ambiente acolhedor e uma relação próxima com o público, transformando a vinheria em um espaço de aprendizado, boas conversas e paixão pelo vinho. A missão da vinheria é proporcionar aos clientes uma experiência única, com momentos de descoberta e prazer no mundo dos vinhos.

Este repositório contém o **front-end** do site da Vinheria Agnello, que apresenta a história da vinheria, informações de contato, e um guia para ajudar os clientes a escolherem o vinho ideal para diferentes ocasiões.

---

## 🗂️ **Estrutura do Projeto**

O projeto é composto pelas seguintes páginas e arquivos:

### Páginas:

-   **`index.html`**: Página inicial com uma introdução sobre a Vinheria Agnello.
-   **`sobre.html`**: Página dedicada à história da vinheria, informações de contato e formulário para envio de mensagens.
-   **`guia.html`**: Página com um guia interativo sobre como escolher o vinho ideal para diferentes ocasiões.
-   **`style.css`**: Arquivo de estilo que contém a formatação e o design visual de todas as páginas do site.

### Estrutura de pastas:

---

## 👥 **Integrantes do Grupo**

Este projeto foi desenvolvido por um time de estudantes apaixonados por vinhos e tecnologia. Os integrantes do grupo são:

-   **Otavio Inaba**
-   **Henrique Guedes**
-   **Henrique Castro de Matos**

---

## 🌐 **Site Publicado**

Você pode acessar o site completo da **Vinheria Agnello** através do seguinte link no **GitHub Pages**:

🔗 [https://Otaaviio.github.io/CP1-FrontEnd-Vinharia](https://Otaaviio.github.io/CP1-FrontEnd-Vinharia)

> Acesse o site para conhecer melhor a vinheria, suas ofertas e descobrir como escolher o vinho ideal para cada momento!

---

## 💻 **Como Rodar o Projeto Localmente**

Se você deseja testar o projeto localmente ou contribuir com melhorias, siga os passos abaixo:

### 1. Clone o repositório

Abra o terminal e clone o repositório para a sua máquina:

```bash
git clone https://github.com/Otaaviio/CP1-FrontEnd-Vinharia.git
```

## 💫 Efeitos Visuais Implementados

O site da Vinheria Agnello conta com uma série de efeitos visuais que aprimoram a experiência do usuário e tornam a navegação mais agradável e interativa. Abaixo estão os principais recursos de estilo aplicados:

### 🎯 Interações com Botões
Botões nas páginas Catálogo e Home (.item-button:active)
➤ Ao serem pressionados, os botões simulam um clique físico:
    • Movem-se 2px para baixo
    • Aplicam uma sombra em tom vinho escuro #800020

Botão do formulário na página Sobre (form button:hover)
➤ Ao passar o mouse, o botão muda de cor para #a60000 (vermelho escuro), evidenciando a ação de envio.

### 🌬️ Animações de Entrada
Página Catálogo:
➤ Os itens surgem suavemente com uma animação personalizada:

Itens em posições pares deslizam da direita para o centro

Itens em posições ímpares deslizam da esquerda para o centro

Tempo de animação: 1s com efeito ease-out

### ✨ Outros Efeitos Visuais
Navbar (:hover)
➤ Destaque visual ao passar o cursor nos links de navegação.

Inputs do formulário (:focus)
➤ Estilização especial ao focar nos campos de texto, melhorando a acessibilidade.

Seções "Uvas" e "Guia" (::before)
➤ Elementos decorativos inseridos antes dos títulos, adicionando charme e identidade visual.

Seleção de texto (::selection)
➤ Seleção personalizada de textos com cores específicas da marca.

Imagens interativas (:hover)
➤ Aplicado nas imagens da Home e da aba Guia de Uvas, adicionando um leve zoom ou destaque ao passar o cursor.

Logo da Home (transform: rotate)
➤ A logo possui um leve efeito de rotação para criar dinamismo e simpatia visual.

Elementos na aba Guia de Uvas (transform: translate)
➤ Aplicado para transições suaves que deslocam elementos horizontalmente durante a navegação.