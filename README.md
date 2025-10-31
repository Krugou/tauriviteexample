# Tauri + Vite Example

A modern example application built with Tauri and Vite, featuring a TypeScript frontend and Rust backend.

## 🚀 Features

- ⚡️ **Vite** - Lightning-fast frontend build tool
- 🦀 **Tauri** - Secure, lightweight desktop application framework
- 📘 **TypeScript** - Type-safe JavaScript
- 🎨 **Modern UI** - Clean and responsive design with dark mode support

## 📋 Prerequisites

Before running this project, make sure you have installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [Rust](https://www.rust-lang.org/tools/install)
- [System dependencies for Tauri](https://tauri.app/start/prerequisites/)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/Krugou/tauriviteexample.git
cd tauriviteexample
```

2. Install dependencies:
```bash
npm install
```

## 💻 Development

### Run as Web Application

To run the frontend as a web application (without Tauri):

```bash
npm run dev
```

Then open [http://localhost:1420](http://localhost:1420) in your browser.

### Run as Desktop Application

To run the full Tauri desktop application:

```bash
npm run tauri dev
```

## 🏗️ Building

### Build Web Application

To build the frontend for production:

```bash
npm run build
```

The output will be in the `dist/` directory.

### Preview Web Build

To preview the production build:

```bash
npm run preview
```

### Build Desktop Application

To build the Tauri desktop application:

```bash
npm run tauri build
```

The executable will be generated in `src-tauri/target/release/`.

## 📁 Project Structure

```
tauriviteexample/
├── src/                  # Frontend source files
│   ├── assets/          # Static assets (logos, images)
│   ├── main.ts          # Main TypeScript entry point
│   └── styles.css       # Global styles
├── src-tauri/           # Tauri (Rust) backend
│   ├── src/             # Rust source files
│   │   ├── lib.rs       # Library with Tauri commands
│   │   └── main.rs      # Application entry point
│   ├── Cargo.toml       # Rust dependencies
│   └── tauri.conf.json  # Tauri configuration
├── index.html           # HTML entry point
├── package.json         # Node.js dependencies
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite configuration
```

## 🎯 Features Demonstrated

- **Tauri Commands**: Communication between frontend (TypeScript) and backend (Rust)
- **Vite HMR**: Hot Module Replacement for fast development
- **TypeScript**: Type-safe code with full IDE support
- **Responsive Design**: Mobile-friendly UI with dark mode

## 🔗 Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/)
- [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) extension
- [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) extension

## 📚 Learn More

- [Tauri Documentation](https://tauri.app)
- [Vite Documentation](https://vite.dev)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)
