# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:-

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# How to run the project on localhost
- Webpage will be accessible at http://localhost:5173/
- We need docker installed on our laptop
- We need vscode IDE
- Install Dev Containers vscode extension
- Open the project in vscode
- Type CMD+Shift+P and Select Dev Containers: Rebuild Container and enter
- It should load required nodejs image as mentioned inside .devcontaner/devcontainer.json
- Open Terminal in vscode using Terminal -> New Terminal
- Type: npm install to install packages
- Type: npm run dev - it should run the frontend project and frontend should be accessible at http://localhost:5173/