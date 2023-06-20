# Programa Desenvolve 2023 - React: conhecendo a biblioteca React Router

Repositório criado com o objetivo de registrar meu progresso no Programa Desenvolve 2023 do Grupo Boticário em parceria com a Alura praticando o que foi abordado nas aulas do curso: <br> 
React: conhecendo a biblioteca React Router, avançando no projeto do restaurante [Aluroni](https://github.com/whoisbrizza/aluroni-react-com-typescript), aprendemos a usar a nova versão do react-router-dom para criarmos rotas na aplicação. <br><br>
Iniciamos apenas com a rota de cardápio, então, criamos a página inicial, no início colocamos o "menu" para funcionar, criamos a página de início e o arquivo routes.tsx para ter a transição de rotas e saber quais as rotas que existem na aplicação. <br>
Criamos um link para conseguir navegar para detalhes do prato, sobre, entre outras páginas, no menu utilizamos o link e no botão "Ver mais" usamos o useNavigate do react-router-dom. <br><br>
Selecionando "ver mais" na página criamos os detalhes do prato e esse detalhes do prato também possui uma página que não existe (not found), então, criamos essa página "not found" e outro ponto é que se digitarmos na URL /banana, por exemplo, que não existe, também vai para a tela de "not found". <br><br>
Também usamos o ESLint, para termos um código mais conciso e algumas refatorações, de modo que criamos uma pasta para "components" com componentes usados entre páginas, geramos a pasta de dados, "data", para colocar o cardápio que usamos entre as páginas também, outra de "types" para inserirmos os tipos que reutilizamos entre as páginas.

## Demonstração:
<img src='Aluroni-react-router.gif'>

## Tecnologias utilizadas durante o curso

* React
* Router
* TypeScript
* SCSS

## Tópicos abordados no curso:

* O que é SPA? <br>
* Estrutura básica do Router DOM <br>
* Criando as rotas <br>
* Router DOM Hooks <br>
* Finalizando o projeto <br>
* Ajustes NotFound e Header <br><br>

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
