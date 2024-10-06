# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### Start Project
- `npm create vite@latest react-jobs`
- Select a framwork: `React`
- Select a variant: `JavaScript`
- `cd react-jobs`
- `code .`
#### Git:
- `git init`
- `git status`
- `git add .`
- `git commit -m "..."`
- `git remote -v`
- `git push origin main`
#### 
- `npm install`
- `npm run dev`

#### Extension
- ES7 React/Redux/GraphQL/React-Native snippets
- Multiple cursor case preserve

#### Install Tailwind
- `npm install -D tailwindcss postcss autoprefixer`
- `npx tailwindcss init -p`
- re-run npm

#### Icons
- `npm i react-icons`

#### router
- `npm i react-router-dom`

#### JSON Server setup
- `npm i -D json-server`
- package.json file add `"server": "json-server --watch src/jobs.json --port 8000"`
- `npm run server`

#### Loading spinner
- `npm i react-spinners`