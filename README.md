# Portfólio — Wesley Portugal Azevedo Silva

Portfólio pessoal de desenvolvimento de software. Estudante de Engenharia de Software
(UNINTER) em busca do primeiro estágio na área de desenvolvimento.

🔗 **Site:** _adicione a URL após o deploy_

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
    └── Wesley-Portugal-Azevedo-Silva-CV.pdf
```

## Rodando localmente

Por ser um site estático, basta abrir o `index.html` no navegador. Para servir com um
servidor local:

```bash
npx serve .
# ou
python -m http.server 8000
```

## Deploy

Compatível com qualquer hospedagem de site estático:

- **Netlify:** arraste a pasta em app.netlify.com/drop, ou conecte o repositório
- **Vercel:** `vercel` na raiz do projeto
- **GitHub Pages:** Settings → Pages → branch `main` / pasta `/root`

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
