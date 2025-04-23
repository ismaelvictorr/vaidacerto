# VetAssist AI

Sistema de assistência veterinária usando IA.

## Requisitos

- Node.js (versão 14 ou superior)
- NPM (gerenciador de pacotes do Node.js)

## Instalação

1. Clone este repositório
2. Instale as dependências:
```bash
npm install
```
3. Copie o arquivo `.env.example` para `.env` e configure sua chave API da Anthropic:
```bash
ANTHROPIC_API_KEY=sua_chave_api_aqui
PORT=3000
```

## Executando o projeto

1. Inicie o servidor:
```bash
npm start
```

2. Abra o arquivo `index.html` em seu navegador

O servidor estará rodando em `http://localhost:3000`

## Desenvolvimento

Para desenvolvimento com reload automático, use:
```bash
npm run dev
```

## Estrutura do Projeto

- `server.js` - Servidor Node.js que atua como proxy para a API da Anthropic
- `index.html` - Interface do usuário
- `.env` - Arquivo de configuração com variáveis de ambiente
- `public/` - Arquivos estáticos servidos pelo servidor

## Funcionalidades

- Interface intuitiva para fazer perguntas sobre veterinária
- Categorização de perguntas por área
- Histórico das últimas 5 perguntas
- Respostas formatadas em Markdown
- Design responsivo

## Tecnologias utilizadas

- HTML5
- TailwindCSS
- JavaScript
- OpenAI API
- Marked.js para renderização de Markdown 