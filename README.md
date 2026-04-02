# 🤝 Connect: Projetos Sociais que Transformam

A **Connect** nasce com o propósito de criar pontes entre o setor corporativo e iniciativas sociais impactantes, facilitando o engajamento em causas de educação, tecnologia, meio ambiente e assistência social.

Diferente de uma página estática simples, este projeto aplica conceitos avançados de **Single Page Application (SPA)**, garantindo uma navegação fluida e uma interface moderna e responsiva.

🚀 **Deploy oficial:** [Visite a Connect](https://connect-empower5-0.vercel.app/)

---

## 💻 Tecnologias & Ferramentas

* **React.js**: Biblioteca principal para construção de interfaces baseadas em componentes.
* **Vite**: Ferramenta de build de última geração para um desenvolvimento ultra-rápido.
* **React Router Dom**: Gerenciamento de rotas e navegação entre páginas.
* **Sass (SCSS Modules)**: Estilização avançada com escopo local, evitando conflitos de classes e permitindo o uso de variáveis e aninhamento.
* **Hooks (useState)**: Gerenciamento de estado para renderização dinâmica de dados.

---

## 🎯 Objetivos Pedagógicos (Front-End)

Neste projeto, consolidamos pilares fundamentais do desenvolvimento Front-End:

* **Componentização:** Divisão da interface em partes reutilizáveis e independentes (NavBar, Footer, Cards).
* **Roteamento Dinâmico:** Implementação de navegação sem recarregamento de página.
* **Responsividade:** Uso de `Media Queries` para garantir que a plataforma funcione perfeitamente em dispositivos móveis e desktops.
* **Manipulação de Arrays:** Renderização dinâmica de componentes utilizando o método `.map()`.
* **Organização de Assets:** Gestão eficiente de imagens e ícones dentro da estrutura `src/assets`.

---

## 📂 Estrutura do Projeto

A arquitetura foi pensada para ser escalável e organizada:

* `src/components/`: Contém pastas individuais para cada componente, separando a lógica (`.jsx`) da estilização (`.module.scss`).
* `src/assets/`: Repositório de imagens e ícones utilizados na interface.
* `App.jsx`: Componente mestre que orquestra a exibição da `NavBar` e do `Footer`.
* `main.jsx`: Ponto de entrada do React que renderiza a aplicação no DOM.
* `global.scss`: Definições globais de reset, fontes e estilos base para todo o projeto.

---

## 🧠 Lógica de Destaque: Componente Ações

Um dos pontos altos do projeto é o componente **Ações da Connect**. Em vez de repetir código manualmente, utilizamos um **Estado (`useState`)** para armazenar um array de objetos. 

Isso simula como uma aplicação real recebe dados de uma API, permitindo que a interface seja gerada automaticamente através de uma iteração, tornando o código limpo, profissional e fácil de manter.

---

## ▶️ Como Executar Localmente

### 1. Clone o repositório
```bash
git clone [https://github.com/NandaCorreaa/Connect_Social_Project.git](https://github.com/NandaCorreaa/Connect_Social_Project.git)
```
---

### 2. Instale as dependências

```bash
npm install
```

### 3. Inicie o servidor de desenvolvimento

```bash
npm run dev
```
---

👩‍🏫 Sobre a Autora
Desenvolvido por Fernanda Correa, Instrutora de Desenvolvimento Full Stack. Este projeto reflete o compromisso em ensinar tecnologias de ponta através de temas que estimulem a responsabilidade social e o impacto positivo na comunidade.

Se este projeto ajudou você a entender como conectar tecnologia e causas sociais através do React, deixe uma ⭐ no repositório!

---

![Preview do Projeto](https://github.com/user-attachments/assets/aff21eb1-ce36-4b3b-934e-f6e1783aef24)
