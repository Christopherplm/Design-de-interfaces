# 🇧🇷 História do Brasil: Da Colônia à Democracia

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

Site informativo e responsivo desenvolvido para a disciplina de **Interface Web** (IFRS Rio Grande) — **Trabalho 3 (CSS Final)**. Apresenta uma linha do tempo sobre os marcos fundamentais da construção do Brasil, do período colonial à redemocratização.

---

## 📌 Visão Geral
O site percorre os principais processos de transição e conflitos sociais do país, com uma interface limpa, temática (estilo papel antigo) e adaptável a diferentes dispositivos.

### 📖 Conteúdo Histórico
O conteúdo está organizado cronologicamente:
* **Brasil Colônia:** economia açucareira e escravidão.
* **Império:** independência e o Segundo Reinado.
* **República Velha:** café com leite e tensões sociais.
* **Era Vargas:** industrialização e direitos trabalhistas.
* **Ditadura Militar:** anos de chumbo e o movimento "Diretas Já".
* **Nova República:** a redemocratização e a Constituição de 1988.

---

## ✨ Novidades do Trabalho 3
* **Formulário "Sugira um Conteúdo":** campos de tipos diferentes (texto, e-mail, data, seleção, opções e mensagem), com `labels` e `fieldsets`, organizado em **CSS Grid** (figura ao lado em telas grandes, abaixo em telas pequenas).
* **Painel Histórico:** mosaico de 5 fotos montado em **CSS Grid** com `background-image` + `background-size: cover`, numerado e com legenda enumerada.

---

## 🛠️ Especificações Técnicas

### HTML Semântico
* Tags estruturais: `<header>`, `<nav>`, `<main>`, `<section>`, `<figure>`, `<form>` e `<footer>`.
* **Metatags** para SEO (Google) e **Open Graph** para redes sociais.
* Navegação interna por âncoras.

### CSS organizado em boilerplate
* Código distribuído em **5 arquivos**: `modern-normalize.css`, `variables.css`, `base.css`, `layout.css` e `components.css`.
* **Variáveis (`:root`)** para centralizar a paleta de cores.
* **Flexbox** (menu e galeria) e **Grid** (formulário e painel).
* **Responsividade** com `@media queries`, funcionando de **375px até 1920px**.

### Imagens otimizadas
* Todas as imagens foram convertidas para **WebP** e redimensionadas para reduzir o peso e melhorar a performance.

---

## 📂 Estrutura do Projeto
```
Design-de-interfaces/
├── index.html
├── css/
│   ├── modern-normalize.css
│   ├── variables.css
│   ├── base.css
│   ├── layout.css
│   └── components.css
├── img/
└── README.md
```

---

## 🚀 Como Clonar e Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Christopherplm/Design-de-interfaces.git
   ```
2. Entre na pasta e abra o `index.html` no navegador (ou acesse pelo GitHub Pages).

---

## 👤 Autor
**Christopher Pereira Lopes** — Interface Web, IFRS Rio Grande.
