# Atividade Avaliativa: Componentização com Props em Next.js

## Objetivo

Desenvolver uma aplicação de compartilhamento de memes utilizando Next.js 15, aplicando conceitos de componentização com props e CSS Modules.

## Contexto

Você foi contratado para trabalhar como desenvolvedor frontend no "MemeVerse", uma plataforma de compartilhamento de memes voltada para adolescentes e jovens adultos. O time de design já criou uma interface completa, e agora você precisa implementar essa interface usando Next.js 15, focando em componentização e reutilização de código.

## Instruções de instalação e execução

1. No terminal, realizar o comando `npx create-next-app@latest nome-do-projeto`;
2. Responder à perguntas da criação do projeto como:
    - Ok to proceed? y
    - TypeScript - No
    - ESLint - Yes
    - Tailwind CSS - No
    - `src/` directory - Yes
    - App Router - Yes
    - Turbopack for `next dev` - Yes
    - import alias - No
3. Acessar o diretório do projeto com `cd nome-do-projeto`;
4. Mudar o nome dos arquivos `layout.js e page.js` para `layout.jsx e page.jsx`;
5. Executar o comando `npm run dev` para iniciar o servidor de desenvolvimento;
6. Acessar o projeto no navegador em `http://localhost:3000`;

## Descrição dos componentes criados

- **Header**: Componente de cabeçalho que exibe o título da aplicação e um botão de login.

- **Hero Section**: Seção principal que apresenta o meme do dia.

- **Interaction Bar**: Componente que contém botões para curtir, comentar, compartilhar e salvar o meme.

- **Categories**: Componente que exibe as categorias de memes disponíveis na plataforma.

## Decisões de design tomadas

## Desafios enfrentados e soluções aplicadas

- Desafio: A footer não estava no layout correto.
  - Solução: 

- Desafio: Realização da componentização e props de meme card e interaction bar.
    - Solução: Com a ajuda de uma extensão do VsCode, a solução foi criar um componente de meme card e interaction bar, utilizando props para passar as informações necessárias.