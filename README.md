# Portfólio — Wesley Portugal

Portfólio pessoal de desenvolvimento de software. Estudante de Engenharia de Software
(UNINTER) em busca do primeiro estágio na área de desenvolvimento de software.

🔗 **Site:** _https://wesleyportugalportfolio.netlify.app_

## Sobre este projeto

Site estático de página única, sem dependências de build:

- **HTML5** semântico e acessível (skip link, landmarks, `alt`, foco visível)
- **CSS3** puro — layout responsivo, tema claro/escuro com `prefers-color-scheme` e persistência em `localStorage`
- **JavaScript** vanilla — troca de tema, animações de entrada com `IntersectionObserver`, respeito a `prefers-reduced-motion`
- Fontes: Inter e Sora (Google Fonts)

## Estrutura

```
.
├── index.html      # conteúdo e marcação
├── styles.css      # estilos e design tokens
├── script.js       # tema, scroll reveal, ano do rodapé
└── assets/
    ├── wesley-portugal.png
    ├── favicon.svg
    └── Wesley-Portugal-CV.pdf
```

## Rodando localmente

Por ser um site estático, basta abrir o `index.html` no navegador. Para servir com um
servidor local:

```bash
npx serve .
# ou
python -m http.server 8000
```

## Projetos em destaque

| Projeto | Descrição | Stack | Links |
| --- | --- | --- | --- |
| CodeSplain IA | Explicações de código em linguagem simples geradas por IA | React, Vite, Node, Express, LLM | [código](https://github.com/wesleyportugalf5/code-splain-ia) · [demo](https://codesplainia.netlify.app/) |
| Lista de Tarefas | Gerenciador de tarefas com foco em produtividade | Next.js, TypeScript, Prisma | [código](https://github.com/wesleyportugalf5/lista-de-tarefas) · [demo](https://listadetarefasprodutividade.vercel.app/) |
| Pac-Man JS | Clássico Pac-Man no navegador com JavaScript puro | Vanilla JS, HTML5, CSS3 | [código](https://github.com/wesleyportugalf5/pacman-js) · [demo](https://jogopacmanjs.netlify.app/) |

## Contato

- **E-mail:** wesleyportugal250@gmail.com
- **WhatsApp:** +55 19 99175-0196
- **LinkedIn:** https://www.linkedin.com/in/wesleyportugal
- **GitHub:** https://github.com/wesleyportugalf5
