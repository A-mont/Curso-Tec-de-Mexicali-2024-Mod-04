# Tutorial Básico de React

Este tutorial proporciona una introducción rápida a React, una biblioteca de JavaScript para construir interfaces de usuario interactivas. 

## 1. Instalación de React

Asegúrate de tener [Node.js](https://nodejs.org/) instalado en tu máquina. Luego, puedes crear un nuevo proyecto de React utilizando [Create React App](https://create-react-app.dev/):

```bash
npx create-react-app mi-primer-dapp
cd mi-primer-dapp

```
o para typescript
```bash
npx create-react-app my-primer-dapp --template typescript
cd mi-primer-dapp

```


Explora la estructura de archivos generada por Create React App. Los archivos principales incluyen:

src/: Contiene los archivos fuente de tu aplicación.
public/: Contiene archivos estáticos como el archivo HTML principal.



## 2: Componentes en React

En React, construimos aplicaciones mediante componentes. Un componente es una parte reutilizable de la interfaz de usuario. Aquí hay un ejemplo de un componente funcional:

```javascript
import React from 'react';

const ComponenteEjemplo = () => {
  return (
    <div>
      <h1>Hola, este es un componente de React</h1>
    </div>
  );
}

export default ComponenteEjemplo;

```


## 3:  Renderizando Componentes


Para usar el componente que creamos, puedes importarlo en tu archivo principal (src/index.js) y renderizarlo en la aplicación:


```javascript

// src/index.js

import React from 'react';
import ReactDOM from 'react-dom';
import ComponenteEjemplo from './ComponenteEjemplo';

ReactDOM.render(
  <React.StrictMode>
    <ComponenteEjemplo />
  </React.StrictMode>,
  document.getElementById('root')
);

```


## 4: Iniciando la Aplicación

Inicia tu aplicación ejecutando el siguiente comando en la terminal:

```bash
npm start
```

## 5: RECOMENDACION: Instalar yarn 

Asegúrate de tener Yarn instalado en tu sistema. Puedes instalarlo utilizando npm con el siguiente comando:

```bash
npm install -g yarn
```

Inicia tu aplicación ejecutando el siguiente comando en la terminal:

```bash
yarn start
```
