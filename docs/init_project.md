---
sidebar_position: 1
---

# Creation of the projet

## Init

```
npx create-react-app {project_name} --template typescript
```
If you have a version problem :
```
npx create-react-app@latest {project_name} --template typescript
```

```
cd {project_name}
npm start
```

## Modify files

```text title="app.tsx"
// highlight-start
import React from 'react';
import './App.css';

function App() {
  return (
    <div className="App">
    </div>
  );
}

export default App;
// highlight-end
```

```text title="index.tsx"
// highlight-start
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';

const root = ReactDOM.createRoot(
  document.getElementById('root') as HTMLElement
);
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
// highlight-end
```

```text title="App.css"
// highlight-start
.App {
  text-align: center;
}
// highlight-end
```

```text title="index.css"
// highlight-start
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
    sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

code {
  font-family: source-code-pro, Menlo, Monaco, Consolas, 'Courier New',
    monospace;
}
// highlight-end
```

:::tip

Delete other files in src/

:::

Start your project :
```text
npm start
```
