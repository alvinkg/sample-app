# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

[Using Bootstrap with React: Tutorial with examples 30 Sep 2023](https://blog.logrocket.com/using-bootstrap-react-tutorial-examples/)


completed the first app ThemeSwitcher in bootstrap-1
need to update the github code and delete the directory local

# second app
alvinlim@coolhandsg-iMac sample-app % npm create vite@latest .

select template / framework React
select vaiant: Javascript (vanilla)

alvinlim@coolhandsg-iMac sample-app % npm install axios bootstrap reactstrap 

 Axios is a promise-based HTTP client for the browser and Node.js. It will enable us to fetch posts from the Bacon Ipsum JSON API.



alvinlim@coolhandsg-iMac sample-app % npm run dev


# modified the src/main.js

import React from 'react'
import ReactDOM from 'react-dom/client'
import App from './App.jsx'
import './index.css'

// Bootstrap CSS
import "bootstrap/dist/css/bootstrap.min.css";
// Bootstrap Bundle JS
import "bootstrap/dist/js/bootstrap.bundle.min";

ReactDOM.createRoot(document.getElementById('root')).render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
)
