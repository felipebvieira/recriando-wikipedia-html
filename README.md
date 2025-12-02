# 🎮 Desafio: Recriando a Wikipedia com HTML Semântico e Acessível

![Badge de HTML5 Válido](https://img.shields.io/badge/HTML5-Válido-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge de Foco em Acessibilidade](https://img.shields.io/badge/Foco-Acessibilidade-2A7AE4?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAxMmMtMi43NiAwLTUgMi42OS01IDYgMCAzLjMwNCA1IDIuMDI5IDUgMi4wMjlzNSAxLjI3NSA1LTIuMDM5YzAtMy4zMDQtMi4yMzYtNi01LTYgMCIwIDAgMCAwIDB6TTExLjE1OCAxNi40NWMtLjc4NC40MjgtMS43OTIuNjk2LTIuMTU4Ljk1LTEuMDMgLjc5LS42OTIgMS45MzUgMS45NSA1LjU4NiAyLjY0Mi0zLjY1IDMuNTE1LTYuOTcxIDItNy43OC0uOTItLjYxNy0yLjE4OC0uNjMzLTIuOTE0Ljk1em0tLjM5MS0uNTg3YzEuMTU1LS4zNzYgMi40MjgtLjM3NiAzLjU4MiAwIDEuNDc0Ljc1MyAxLjU2OSAyLjA2NS0yLjg5NyA1Ljk0Mi00LjQ2Ni0zLjg3Ny00LjM3MS01LjE4OS0yLjQyOC01Ljk0MnptMS42MzMtMS40OTdDMTEuMzcyIDUuODcgMTAuNTE4IDQgOS4yNzQgNGMtLjk0IDAtMS42NTcuODcxLTEuNjU3IDEuOTQyIDAgMS4wNy42OSA1Ljk4NiAxLjY1NyA1Ljk4NnMuNDQtMS45MDcgLjg4NC0zLjMyN2wxLjUyMS0uNzY2bDIuNzIxLjc1N2wuMzY1Ljk0Mi0xLjcyNC0uMjM4Yy0uOTc0LS4xMzItMS44OTktLjQxOS0yLjY3Ni0uNzc5em0wIDEuNS4xMTkuNDI5Ljk5OC0uMzIgMS40NTgtLjk2LjY5Ny0uMjM4IDEuNTIuNTkxLS4zNjUgMS41NTYtMS42NDIgMi4wNDYtMS44OTcuODg1em0yLjk0Ny0xLjk5MmMwIC44MTUtLjY1NCAxLjQ3My0xLjQ2MyAxLjQ3My0uODEgMC0xLjQ2My0uNjU4LTEuNDYzLTEuNDczIDAtLjgyNi42NTMtMS40OTkgMS40NjMtMS40OTkuODEgMCAxLjQ2My42NzMgMS40NjMgMS40OTl6TTEyIDJjNS41MjMgMCAxMCA0LjQ3NyAxMCAxMHMtNC40NzcgMTAtMTAgMTAtMTAtNC40NzctMTAtMTBzNC40NzctMTAtMTAtMTB6Ii8+PC9zdmc+)

---

## 💡 Sobre o Projeto

Este projeto consiste na resolução de um desafio técnico focado na criação da **estrutura e semântica de páginas web** inspiradas no layout e na organização de artigos da **Wikipedia**. O ponto principal do desafio foi a **proibição de uso de CSS**, forçando a organização do conteúdo a ser definida *apenas* pelo HTML, garantindo robustez estrutural e acessibilidade.

O trabalho demonstra o domínio na correta utilização de elementos estruturais do HTML5.

### 🔗 Páginas Navegáveis

| Artigo | Descrição | Status Semântico | Link |
| :--- | :--- | :--- | :--- |
| **Home/Games** | Página principal e categoria de Games. | ✅ Alto | [Acessar `index.html`](index.html) |
| **Street Fighter** | Artigo detalhado sobre o jogo. | ✅ Alto | [Acessar `street-fighter.html`](street-fighter.html) |
| **Mortal Kombat** | Artigo detalhado sobre o jogo. | ✅ Alto | [Acessar `mortal-kombat.html`](mortal-kombat.html) |
| **League of Legends** | Artigo detalhado sobre o jogo. | ✅ Alto | [Acessar `league-of-legends.html`](league-of-legends.html) |

---

## 🛠️ Destaques Técnicos

O projeto implementa as seguintes boas práticas de HTML5 e Acessibilidade:

### 1. Semântica Estrutural

* **Elementos Regionais:** Uso de `<header>`, `<main>`, `<aside>`, `<section>`, `<nav>` e `<footer>` para definir claramente o papel de cada bloco de conteúdo no documento.
* **Hierarquia de Títulos (`H1-H4`):** O conteúdo está estruturado com a ordem correta de títulos, crucial para a indexação e para a navegação de leitores de tela.
* **Mídia Associada:** Utilização do par **`<figure>`** e **`<figcaption>`** para garantir que as imagens estejam semanticamente ligadas às suas respectivas legendas.
* **Informações de Autoria/Licença:** O `<footer>` utiliza a tag **`<address>`** para envolver as informações de licença do conteúdo, conforme a recomendação de HTML5 para informações de contato/autoria.

### 2. Acessibilidade (ARIA e Links)

* **`aria-label` em Navegações:** Para diferenciar múltiplas ocorrências da tag `<nav>` na página (navegação principal e índice do artigo), o atributo `aria-label` foi utilizado. Isso permite que usuários de tecnologias assistivas entendam o propósito de cada menu.
    * *Ex:* `<nav aria-label="Conteúdo deste artigo">`
* **`alt` Descritivo:** Todas as imagens relevantes possuem o atributo `alt` com descrições concisas e contextuais (ex: Logotipo da Fundação Wikimedia), auxiliando na navegação sem visualização.
* **Âncoras de Navegação:** O índice lateral ("Neste Artigo") é construído com **links internos (`#id`)**, permitindo que o usuário pule rapidamente entre as seções do artigo.

---

## 🚀 Como Executar o Projeto

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/felipebvieira/recriando-wikipedia-html]
    ```

2.  **Abra o Arquivo:**
    Navegue até a pasta do projeto e abra o arquivo `index.html` diretamente no seu navegador de preferência.

    ```bash
    cd nome-do-projeto
    open index.html # (Em sistemas Unix/macOS)
    start index.html # (Em sistemas Windows)
    ```

3.  **Explore:**
    Utilize a barra lateral para navegar entre os artigos de Games (`Street Fighter`, `Mortal Kombat`, `League of Legends`).

## links dos sites da wikipedia utilizados
- index https://pt.wikipedia.org/wiki/Jogo_eletr%C3%B4nico
- street fighter https://pt.wikipedia.org/wiki/Street_Fighter
- mortal kombat  https://pt.wikipedia.org/wiki/Mortal_Kombat
- league of legends https://pt.wikipedia.org/wiki/League_of_Legends