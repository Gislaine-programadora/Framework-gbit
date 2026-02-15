<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <!-- Fundo gradiente escuro -->
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="50%" style="stop-color:#1a0f0f"/>
      <stop offset="100%" style="stop-color:#0a0a0a"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Fundo -->
  <rect width="1200" height="300" fill="url(#bg)"/>
  
  <!-- Comandos CLI de exemplo -->
  <g fill="#00ff88" opacity="0.12">
    <text x="60" y="85" font-family="monospace" font-size="16">npx create-gbit-app my-projeto</text>
    <text x="60" y="125" font-family="monospace" font-size="14">cd my-projeto</text>
    <text x="60" y="165" font-family="monospace" font-size="14">$ npm run stake</text>
    <text x="60" y="205" font-family="monospace" font-size="12">✅ Smart contracts deployed!</text>
    <text x="850" y="110" font-family="monospace" font-size="16" opacity="0.08">npm i create-gbit-app</text>
  </g>
  
  <!-- Logo principal: create-gbit-app -->
  <g filter="url(#glow)" font-family="'JetBrains Mono', 'Fira Code', monospace" font-weight="900">
    <!-- "create-" em cinza -->
    <text x="180" y="175" font-size="32" fill="#888888" stroke="#aaaaaa" stroke-width="1">create-</text>
    <!-- "gbit-app" em vermelho glow -->
    <text x="380" y="185" font-size="68" fill="#ff4444" stroke="#ff6666" stroke-width="2">GBIT</text>
    <text x="580" y="185" font-size="68" fill="#ff4444" stroke="#ff6666" stroke-width="2" font-weight="700">APP</text>
  </g>
  
  <!-- Tagline -->
  <g font-family="'JetBrains Mono', monospace" font-size="24" fill="#cccccc" opacity="0.95">
    <text x="180" y="235" text-anchor="middle">The fastest way to bootstrap Web3 staking apps</text>
  </g>
  
  <!-- Ícone Node.js + Ethereum -->
  <g transform="translate(980, 135)">
    <!-- Node.js hex -->
    <polygon points="0,25 13,8 26,8 39,25 26,42 13,42" fill="#68a063" opacity="0.7"/>
    <!-- ETH diamante -->
    <polygon points="20,10 30,20 20,30 10,20" fill="#627eea" stroke="#8f9bff" stroke-width="1.5" opacity="0.8"/>
  </g>
  
  <!-- Cursor piscando -->
  <text x="1150" y="195" font-family="monospace" font-size="24" fill="#00ff88" opacity="0.6">_</text>
  
  <!-- Borda inferior -->
  <rect y="290" width="1200" height="10" fill="#ff4444" opacity="0.25"/>
</svg>


<div align="center">
  <img src="./src/assets/gbit-logo.png" alt="Gbit Framework Logo" width="192" height="192" />
</div>
 <div align="center">


## GBit — The All-in-One Modern Project GeneratoR
  
GBit is a powerful open-source tool designed for modern developers. With a single command, it creates a complete project structure — including backend, frontend, and smart contracts — ready to build and deploy.

Use the command:

```bash
 npx create-gbit-app@latest "meu-projeto"
```
                          
GBit also comes with an optimized build tool:

```bash
 npx gbit-build
```
💡 Open Source | Fast | Modern | Developer-Gbit


<div align="center">

<img src="./assets/hero-computer.png" alt="Gbit Framework Hero" width="860">

<h1>Gbit Framework</h1> <p>Crie aplicações completas — Frontend, Backend e Smart Contracts — prontas para produção.</p>

<a href="#instalação" style="text-decoration:none;"> <img src="https://img.shields.io/badge/Instalar-agora-1a73e8?style=for-the-badge&logo=npm&logoColor=white" alt="Instalar agora"> </a> <a href="#demo" style="text-decoration:none;"> <img src="https://img.shields.io/badge/Ver%20demo-10b981?style=for-the-badge" alt="Ver demo"> </a> <a href="https://portfolio.metamask.io" target="_blank" style="text-decoration:none;"> <img src="https://img.shields.io/badge/MetaMask%20Portfolio-f97316?style=for-the-badge&logo=metamask&logoColor=white" alt="MetaMask Portfolio"> </a>

</div>



# Gbit  Framework  

[![npm version](https://img.shields.io/npm/v/create-gbit-app.svg)](https://www.npmjs.com/package/create-gbit-app)


  ##  GBit — The All-in-One Modern Project Generator
  
GBit is a powerful open-source tool designed for modern developers. With a single command, it creates a complete project structure — including backend, frontend, and smart contracts — ready to build and deploy.

Use the command:

```bash
 npx create-gbit-app@latest "meu-projeto"
```
                          
GBit also comes with an optimized build tool:

```bash
 npx gbit-build
```
💡 Open Source | Fast | Modern | Developer-Gbit

### Crie aplicações completas — Backend, Frontend e Smart Contracts

[![NPM Version](https://img.shields.io/npm/v/create-gbit-app.svg)](https://www.npmjs.com/package/create-gbit-app)
[![License](https://img.shields.io/npm/l/create-gbit-app.svg)](https://github.com/Gislaine-programadora/create-gbit-app/blob/main/LICENSE)

</div>

## 🚀 Início Rápido

```bash
npx create-gbit-app@Latest meu-projeto
```

### Visual terminal: 

<img width="726" height="623" alt="image" src="https://github.com/user-attachments/assets/5207bb62-a58b-402b-af91-63297dcc2d4e" />

## ✨ Features

- ✓ **Backend Completo** - Node.js ou Python com Express, Nest.js ou Flask
- ✓ **Frontend Moderno** - React, Next.js ou Vite com TypeScript e Tailwind CSS
- ✓ **Smart Contracts** - Solidity ou Vyper com scripts de deploy automáticos
- ✓ **Docker Ready** - Docker e Docker Compose configurados automaticamente

## 🎯 O que é o Gbit Framework?

O Gbit Framework é uma ferramenta CLI que permite criar aplicações full stack completas em minutos, incluindo:

## https://github.com/Gislaine-programadora/flamework-gbit/blob/main/LICENSE

- **Backend Poderoso**: Node.js ou Python com Express, Nest.js ou Flask. WebSockets, APIs REST e muito mais.
- **Frontend Moderno**: React, Next.js ou Vite com TypeScript. Tailwind CSS e componentes prontos.
- **Blockchain Ready**: Smart contracts em Solidity ou Vyper. Scripts de deploy e ABI automáticos.
- **Pronto para Produção**: Docker, Docker Compose, CI/CD com Vercel. Tudo configurado automaticamente.
  
 <img width="600" height="600" alt="ChatGPT Image 12 de dez  de 2025, 20_04_50" src="https://github.com/user-attachments/assets/24725ce8-fb73-43cf-9864-7f23ea77734b" />
 
## 📦 Instalação

🔗 Link oficial do pacote   https://www.npmjs.com/package/create-gbit-app


### Uso Direto (Recomendado)

```bash
npx create-gbit-app@Latest meu-projeto
```

### Instalação Global

```bash
npm install -g create-gbit-app
create-gbit-app meu-projeto
```

## 🛠️ Tecnologias Suportadas

### Backend
- Node.js (Express, Nest.js)
- Python (Flask)
- WebSockets (Socket.io)

### Frontend
- React + Vite
- Next.js
- TypeScript/JavaScript
- Tailwind CSS

### Smart Contracts
- Solidity
- Vyper
- Hardhat
- Deploy Scripts Automáticos

### Banco de Dados
- PostgreSQL
- MySQL
- MongoDB
- SQLite

### DevOps
- Docker & Docker Compose
- CI/CD Vercel
- Git Configuration

  ## Ferramenta de compilacao use "gbit-build" typeScript/vite:
  
  🧱 gbit-build: ferramenta de build completa


  ```bash
  npx gbit-build

  

O pacote  é responsável por empacotar e preparar seu projeto com comandos simples e poderosos:


<div align="center">
  <img src="assets/gbit-npm.png" alt="Gbit Framework Logo" width="192" height="192" />
</div>


📦 Instalação

```bash
npm install --save-dev gbit-build

...

⚙️ Comandos disponíveis

```bash

npx gbit-build               # Build completo
npx gbit-build --only-frontend
npx gbit-build --skip-docker
npx gbit-build --verbose
npx gbit-build --dry-run
...

O  automatiza o build do frontend, backend e geração de imagem Docker.


## 📖 Documentação

Para mais informações, visite a [documentação completa](https://github.com/gislaine-programadora/create-gbit-app).

 <img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/57d2e542-c9a9-4651-93e9-cfa9be5c8a0f" />


## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

#npm

## 📄 Licença

[![npm version](https://img.shields.io/npm/v/create-gbit-app.svg)](https://www.npmjs.com/package/create-gbit-app)

MIT

---

<div align="center">

**Criado com ❤️ usando Gbit Framework**

[Website](https://gbitframework.com) • [Documentação](https://docs.gbitframework.com) • [GitHub](https://github.com/gislaine-programadora/create-gbit-app)

</div>
