# 🚀 Rollup-TSX

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node.js](https://img.shields.io/badge/Node.js-14.x+-339933.svg?logo=node.js)
![Rollup](https://img.shields.io/badge/rollup-2.x-EC4A3F.svg?logo=rollup.js)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-3178C6.svg?logo=typescript)

Un boilerplate avanzato per librerie Node.js con TypeScript e Rollup. Perfetto per creare pacchetti TypeScript ottimizzati, tipizzati e pronti per la distribuzione.

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Project Setup](#-project-setup)
- [Development](#-development)
- [Build](#-build)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 📦 Bundling ottimizzato con Rollup
- 🔒 Type safety con TypeScript
- 🔍 TypeScript linting con ESLint
- 🎨 Formattazione del codice con Prettier
- 🧪 Testing con Jest e TS-Jest
- 📤 Supporto per import/export ES Modules
- 💾 Funzionalità 100% offline
- 🔄 Supporto per hot-reload durante lo sviluppo
- 📊 Strumenti per generazione documentazione
- 📝 Dichiarazioni di tipo TypeScript (.d.ts)

## 🗂️ Project Structure

```
bl-rollup-node-typescript/
├── dist/               # Output directory per il bundle
├── src/                # Codice sorgente TypeScript
│   ├── index.ts        # Entry point principale
│   └── lib/            # Moduli e funzionalità della libreria
├── test/               # File di test
├── .eslintrc           # Configurazione ESLint
├── rollup.config.js    # Configurazione Rollup
├── jest.config.js      # Configurazione Jest
├── tsconfig.json       # Configurazione TypeScript
└── package.json        # Dipendenze e script del progetto
```

## 🚀 Project Setup

### 📥 Install

```bash
$ pnpm install
```

## 🔧 Development

```bash
$ pnpm dev
```

## 📦 Build

```bash
$ pnpm build
```

## 📦 Package Managers

Questo progetto supporta diversi package manager. Ecco come utilizzare ciascuno:

### NPM

NPM è il package manager predefinito per Node.js.

**Installazione NPM:**
```bash
# Incluso con l'installazione di Node.js
```

**Setup progetto con NPM:**
```bash
# Installazione dipendenze
$ npm install

# Modalità sviluppo
$ npm run dev

# Build della libreria
$ npm run build
```

**Caratteristiche principali:**
- 📚 Vasto ecosistema di pacchetti
- 🔒 Struttura gerarchica di node_modules
- 📋 Package.json per la gestione delle dipendenze

### Yarn

Yarn è un'alternativa rapida, affidabile e sicura a NPM.

**Installazione Yarn:**
```bash
# Installazione tramite NPM
$ npm install -g yarn
```

**Setup progetto con Yarn:**
```bash
# Installazione dipendenze
$ yarn

# Modalità sviluppo
$ yarn dev

# Build della libreria
$ yarn build
```

**Caratteristiche principali:**
- ⚡ Velocità di installazione superiore
- 📦 Caching offline
- 🔒 Maggiore sicurezza con checksum
- 📋 yarn.lock per installazioni deterministiche

### PNPM

PNPM è un package manager efficiente in termini di spazio su disco.

**Installazione PNPM:**
```bash
# Installazione tramite NPM
$ npm install -g pnpm
```

**Setup progetto con PNPM:**
```bash
# Installazione dipendenze
$ pnpm install

# Modalità sviluppo
$ pnpm dev

# Build della libreria
$ pnpm build
```

**Caratteristiche principali:**
- 💾 Risparmio di spazio su disco tramite symlink
- 🚀 Velocità di installazione elevata
- 🔄 Storage con indirizzamento basato sul contenuto
- 📋 pnpm-lock.yaml per blocco delle dipendenze

### Confronto

| Funzionalità          | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Utilizzo disco        | Alto    | Alto    | Basso   |
| Velocità installazione| Lenta   | Veloce  | Velocissima |
| Installazioni parallele| Limitato| Sì      | Sì      |
| Supporto workspaces   | Limitato| Buono   | Ottimo  |
| Modalità offline      | Limitato| Buono   | Buono   |
| Sicurezza             | Buona   | Migliore| Migliore|

## 📚 Resources

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Rollup Documentation](https://rollupjs.org/guide/en/)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
