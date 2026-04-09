# 🏗️ Tecfer Serralheria - Website Oficial

![Status do Projeto](https://img.shields.io/badge/Status-Online-success?style=for-the-badge)
![Tecnologias](https://img.shields.io/badge/HTML5-CSS3-JS%20Vanilla-orange?style=for-the-badge)

Repositório oficial do site da **Tecfer Serralheria**. Um projeto desenvolvido com foco em altíssima performance, conversão de leads e autoridade de marca para o setor de estruturas metálicas.

---

## 🏢 Sobre a Tecfer
Localizada em Serra-ES, a Tecfer combina **34 anos de tradição** com tecnologia de ponta. Somos especialistas em transformar aço em soluções estruturais robustas:
* **Fabricação e Instalação Própria:** Controle total de qualidade sem terceirização.
* **Especialidades:** Galpões industriais, mezaninos, escadas metálicas e coberturas.
* **Diferencial:** Rapidez na entrega e precisão de engenharia.

---

## 🛠️ Especificações Técnicas (Performance & SEO)

O site foi construído seguindo as melhores práticas de **Web Vitals** para garantir que a experiência do usuário seja instantânea, mesmo em conexões móveis limitadas.

### ⚡ Engenharia de Front-end
* **Critical Path Optimization:** As fontes críticas (Montserrat Bold e ExtraBold) e a imagem principal (`BG-Desktop.webp`) possuem `rel="preload"` para reduzir o tempo de renderização inicial (LCP).
* **Zero Dependencies:** Utilização exclusiva de **Vanilla JavaScript**. Sem JQuery ou frameworks pesados, resultando em um bundle extremamente leve e execução rápida.
* **Imagens de Próxima Geração:** Implementação total em formato **WebP**, garantindo economia de banda sem perda de fidelidade visual.
* **CSS Arquitetura:** Uso de variáveis nativas (`:root`) para consistência visual e facilidade de manutenção em temas e cores.

### 🧩 Funcionalidades Implementadas
* **Scroll Reveal:** Sistema de animação nativo via `IntersectionObserver` para engajamento visual.
* **Custom Carousel:** Slider de produtos responsivo com navegação otimizada.
* **Google Reviews Integration:** Modal customizado para exibição de prova social sem comprometer o carregamento da página.
* **FAQ Inteligente:** Sistema de acordeão para melhoria do SEO (Rich Snippets).

---

## 📂 Estrutura de Diretórios

```text
├── index.html          # Estrutura semântica e estilos críticos
├── assets/
│   ├── fonts/          # Fontes Montserrat otimizadas (woff2)
│   ├── img/            # Assets em alta resolução (WebP)
│   └── js/             # Lógica de interatividade e modais