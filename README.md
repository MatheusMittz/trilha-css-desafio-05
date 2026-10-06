# 🎬 Desafio DIO: Clonando o Site da HBO Max com Animações em HTML e CSS

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![CSS Animations](https://img.shields.io/badge/Animations-Keyframes-ff00e5?style=for-the-badge)
![Responsividade](https://img.shields.io/badge/Layout-Responsivo-b535f6?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)

</div>

Projeto prático desenvolvido para o desafio final **"Clonando o Site da HBO Max com Animações em HTML e CSS"**, pertencente à **Trilha CSS Web Developer** da [DIO (Digital Innovation One)](https://www.dio.me/), ministrado pela expert **Michele Ambrosio**.

---

## 📌 Visão Geral do Projeto

O objetivo principal desta aplicação é recriar a interface do serviço de streaming **HBO Max**, aplicando técnicas avançadas de estilização moderna com **HTML5** e **CSS3**, com ênfase especial em:

- **Animações e Transições:** Utilização de `@keyframes`, gradientes animados nos botões e no plano de fundo do cabeçalho.
- **Transformações 2D e 3D:** Cards de planos de assinatura interativos com efeitos de profundidade, escala e iluminação no hover.
- **Grid Layout & Flexbox:** Estruturação da galeria de títulos (filmes e séries por categoria) e menus dinâmicos.
- **Pseudo-classes e Pseudo-elementos:** Validação visual de formulários em tempo real (`:valid`, `:invalid`, `:focus`), tooltips e custom scrollbars.
- **Design Totalmente Responsivo:** Adaptação fluida para resoluções mobile, tablet e desktop.

---

## 🚀 Funcionalidades & Seções

- **Barra de Navegação Fixa (Navbar):**
  - Fundo translúcido com `backdrop-filter` / transparência (`rgba`).
  - Logotipo oficial vetorizado da HBO Max em SVG.
  - Links de navegação para página de autenticação e âncora direta para os planos de assinatura.

- **Hero & Cabeçalho com Animação Dinâmica:**
  - Carrossel de canais e marcas parceiras (HBO, DC, Warner Bros, Cartoon Network, Max Originals).
  - Título com destaque visual e tipografia escalável (`Raleway` e `Quicksand`).
  - Efeito gradiente animado contínuo no botão principal de CTA (*Call to Action*).

- **Cards de Planos de Assinatura (Subscription Plans):**
  - Divisão entre planos Mobile e Multitelas com abas e seletores visuais.
  - Cards com borda gradiente translúcida, listas de benefícios e animação de elevação ao passar o cursor.

- **Catálogo de Filmes e Séries:**
  - Grade responsiva exibindo destaques da plataforma (HBO, Warner Bros, DC, Cartoon Network).
  - Imagens de alta qualidade com transição suave de escala e zoom ao interagir com o card.

- **Página de Login (`signIn.html`):**
  - Formulário centralizado com campos de e-mail e senha.
  - Tratamento e feedback visual nativo em CSS para campos obrigatórios e válidos/inválidos.
  - Links de recuperação de senha e acesso institucional.

- **Barra de Rolagem Personalizada (Custom Scrollbar):**
  - Estilização exclusiva com gradientes da identidade visual da plataforma via `::-webkit-scrollbar`.

---

## 📐 Boas Práticas e Conceitos Aplicados

| Conceito / Recurso | Aplicação no Projeto |
| :--- | :--- |
| **CSS Custom Properties (Variáveis)** | Paleta de cores centralizada no `:root` (`--primary-color`, `--secondary-color`, `--tertiary-color`, etc.) |
| **CSS Keyframes & Transitions** | Animação contínua de gradientes e transições suaves de escala (`transform: scale()`) e opacidade |
| **Flexbox & Grid Layout** | Alinhamento de cabeçalho, distribuição dos cards de assinatura e grid responsivo do catálogo |
| **Tipografia Otimizada** | Importação direta das fontes Google Fonts `Raleway` e `Quicksand` |
| **Acessibilidade & Semântica** | Uso de tags semânticas HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<form>`) |
| **Media Queries** | Breakpoints estruturados para adaptação em telas pequenas, médias e grandes |

---

## 📁 Estrutura de Arquivos

```text
desafio9/
├── assets/
│   ├── css/
│   │   ├── global.css     # Variáveis CSS, reset global, tipografia e scrollbar
│   │   ├── index.css      # Estilização da página principal, hero, planos e catálogo
│   │   └── signIn.css     # Estilização da página de login e validações de formulário
│   └── images/            # Assets visuais (logos, capas de filmes, ícones e marcas)
├── index.html             # Página principal do clone HBO Max
├── signIn.html            # Página de autenticação
├── README.md              # Documentação oficial do projeto
└── .gitignore             # Controle de versão Git
```

---

## 🛠️ Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/MatheusMittz/trilha-css-desafio-05.git
   ```
2. Acesse a pasta:
   ```bash
   cd trilha-css-desafio-05
   ```
3. Abra o arquivo `index.html` em seu navegador web (ou utilize a extensão **Live Server** no VS Code).

---

## 🔗 Referências

- [Repositório Modelo da Instrutora Michele Ambrosio](https://github.com/micheleambrosio/hbomax)
- [Trilha CSS Web Developer na DIO](https://web.dio.me/track/formacao-css-web-developer)
- [Desafio DIO: Clonando o site da HBO Max com animações em HTML e CSS](https://web.dio.me/project/clonando-o-site-da-hbo-max-com-animacoes-em-html-e-css/learning/9d5f9956-a23e-4851-b96b-1d724f23b0da?back=/track/formacao-css-web-developer)

---

## 👤 Autor

Desenvolvido por **[Matheus Mittz](https://github.com/MatheusMittz)**.