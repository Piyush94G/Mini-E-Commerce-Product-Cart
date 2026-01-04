# E-Store

A modern e-commerce web application built with React and Vite, featuring fast refresh and optimized development experience.

## 🚀 Features

- ⚡️ Lightning-fast development with Vite
- ⚛️ React 19 for building user interfaces
- 🎨 Modern and responsive design
- 🔄 Hot Module Replacement (HMR)
- 🛣️ Client-side routing with React Router v7
- 📦 Optimized production builds
- 🔍 ESLint configuration for code quality

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 18.0.0 or higher recommended)
- npm (comes with Node.js)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/e-store.git
cd e-store
```

2. Install dependencies:
```bash
npm install
```

## 🏃 Running the Application

### Development Mode

Start the development server with hot reload:
```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

### Production Build

Build the application for production:
```bash
npm run build
```

### Preview Production Build

Preview the production build locally:
```bash
npm run preview
```

### Linting

Run ESLint to check code quality:
```bash
npm run lint
```

## 📁 Project Structure

```
e-store/
├── src/              # Source files
├── public/           # Static assets
├── dist/             # Production build output
├── node_modules/     # Dependencies
├── index.html        # Entry HTML file
├── vite.config.js    # Vite configuration
├── eslint.config.js  # ESLint configuration
├── package.json      # Project dependencies and scripts
└── README.md         # Project documentation
```

## 🛡️ Built With

- **[React](https://react.dev/)** (v19.2.0) - JavaScript library for building user interfaces
- **[Vite](https://vite.dev/)** (v5.4.8) - Next generation frontend tooling
- **[React Router](https://reactrouter.com/)** (v7.11.0) - Declarative routing for React
- **[ESLint](https://eslint.org/)** (v9.39.1) - Pluggable linting utility for JavaScript

## ⚙️ Configuration

### Vite Configuration

The project uses a minimal Vite configuration with React plugin support. You can customize `vite.config.js` to add additional plugins or modify build settings.

### ESLint Configuration

ESLint is configured with React-specific rules including:
- React Hooks rules
- React Refresh rules
- Modern JavaScript standards
