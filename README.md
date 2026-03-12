# Freelancer Dashboard

Aplicacao em Next.js para controle de projetos de freelancer, com cadastro de projetos, filtro por status e grafico de rendimento mensal.

## Requisitos

- Node.js 20+
- npm 10+

## Rodando localmente

```bash
npm install
npm run dev
```

Abra `http://localhost:3000` no navegador.

## Validacao do projeto

```bash
npm run lint
npm run build
```

## Funcionalidades

- Cadastro de projetos com cliente, nome, valor, prazo e status.
- Persistencia local com `localStorage`.
- Filtro por status (`Todos`, `Em Aberto`, `Concluido`).
- Grafico de receita mensal para projetos concluidos.
- Interface responsiva para desktop e celular.

## Publicar online (Vercel)

1. Suba o projeto para um repositorio no GitHub.
2. Acesse https://vercel.com/new e conecte o repositorio.
3. Mantenha as configuracoes padrao do Next.js.
4. Clique em `Deploy`.

## Publicar online (servidor Node)

```bash
npm install
npm run build
npm run start
```

Por padrao, o app inicia na porta `3000`. Em producao, configure a variavel `PORT` se necessario.
