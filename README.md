## Filmes


* Node.Js
* React
* Bootstrap
* Vscode

-------------------------------------------------------------------

### passo a passo


1- criado o projeto com o comando **npx create-react-app filmes**.

2 - Crie uma pasta dentro de SRC chamado **components** (para criar os components da aplicação).

3 - Dentro da pasta **components** criar as pastas para cada componente **Movie**,**Header**,**Footer**,**Title**.

4 - Para cada componente da pasta foi criado um arquivo chamado **index.js** e um **css** com o nome do componente.

5 - Para estilizar melhor a pagina foi intalado pelo terminal do VScode o bootstrap com o comando **npm install bootstrap**, E Dentro do **src/index.js** foi importado o bootstrap.
  
   ```javascript
            
        import 'bootstrap/dist/css/bootstrap.css';
        
        

  ```

6 - Adicionado coleção de componentes de navegação **react-router-dom** usando o comando **npm install react-router-dom** para utilizar rotas e manipular a navegação do aplicativo.

7 - feito o Import do **react-router-dom** no App.js e a tag <Router></Router> no componente App.js para poder adicionar varios componentes dentro dele e criar as paginas.

   ```javascript

     import { BrowserRouter as Router, Routes, Route, Link } from 'react-router-dom';
     
   ```

   8 - Na pasta public foi criado as pastas **assets/images** para adicionar arquivos de imagens para serem usados no projeto de filme

   9 - foi copiado do site do bootstrap exemplos de estruturas HTML prontas de header,footers,Titles,Cards para adicionar aos respectivos componentes

   10 - criado um array no componente Movies para servir como a base de dados para executar o Map com as informação dos filmes.

   








---------------------------------------------------------------------------------------------------
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
