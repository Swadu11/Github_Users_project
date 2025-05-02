# 🧑‍💻 GitHub Users Viewer – React + Vite

A lightweight, high-performance React application scaffolded with Vite. Designed for building a GitHub user interface or any dynamic data-driven frontend.

## 🚀 Features

* ⚛️ React 19 + Vite for blazing fast development
* 🔄 Hot Module Replacement (HMR) with Fast Refresh
* 🧹 ESLint configuration with React Hooks & Refresh rules
* 📆 Minimal and modern dependency setup
* 🧰 Ready for TypeScript and production scaling

## 📁 Project Structure

```
.
├── public/               # Static assets
├── src/                  # Your React components & logic (entry at main.jsx)
├── index.html            # App container and entry point
├── vite.config.js        # Vite configuration with React plugin
├── eslint.config.js      # ESLint config for code quality
├── package.json          # Project metadata and dependencies
└── .gitignore
```

## 📜 Scripts

```bash
npm install     # Install dependencies
npm run dev     # Start development server
npm run build   # Build for production
npm run preview # Preview the built app
npm run lint    # Run ESLint checks
```

## 🧪 Linting Details

Your ESLint setup includes:

* `@eslint/js` for base JS rules
* `eslint-plugin-react-hooks` to ensure proper use of React hooks
* `eslint-plugin-react-refresh` for safe HMR usage
* A custom rule to ignore unused constants written in `UPPER_CASE`

See `eslint.config.js` for full details.



## 💡 Notes

* Currently built using JSX. For TypeScript support, consider using the [Vite React TS Template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts).
* You can enhance this scaffold with GitHub API integrations or any REST/GraphQL API to display user data.



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
