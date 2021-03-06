/***************************************/

React.js and Redux, Backend is a seed for Symfony4 API

Fork contains proof of concept based on several front end tutorials: judo-heroes2 itself,

https://github.com/sadams/todo-redux-react-webpack

https://github.com/gaearon/todos/tree/master/src

https://github.com/reactjs/redux/tree/master/examples/real-world

https://engineering.thetrainline.com/handling-api-calls-in-redux-with-redux-api-middleware-c95c38816e13

Look at branches to fetch code for each tutorial 
and change https://github.com   to  https://codesandbox.io/s/github  see it in action in code sandbox

In my example React/redux files location is symlinked from public/bundles/tensorcore to

https://github.com/Dodotree/judo-heroes-2/tree/master/site/src/Tensor/CoreBundle/Resources/public/src

Renders page from preloaded JSON and then updates/sync state through API

Below is readme from tutorial used as main code source. Redux states and API handling were added on top of it

/***************************************/


# judo-heroes-2

Universal JavaScript sample application with React Router 4 and Express 5 (Enhanced version of https://github.com/lmammino/judo-heroes)

[![Build Status](https://travis-ci.org/lmammino/judo-heroes-2.svg?branch=master)](https://travis-ci.org/lmammino/judo-heroes-2)
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Setup

```bash
git clone git@github.com:lmammino/judo-heroes-2.git
cd judo-heroes-2
yarn # or `npm i` if not using yarn
```

## Available commands

Available commands to run with `npm run`:

 - `start`: build the production package and run the production server (no universal)
 - `start:universal`: build the production package and run the production server with universal rendering
 - `start:dev`: build the dev package and run the server in dev mode (no universal rendering — auto-restarts on changes)
 - `start:dev:universal`: build the dev package and run the server in dev mode with universal rendering (auto-restarts on changes)
 - `build`: build the production package
 - `build:dev`: build the dev package
 - `build:dev:watch`: build the dev package in watch mode (listen for changes and re-build immediately)


 ## Want to know more about Node.js, React and Universal JavaScript?

 If you want to know more about Universal JavaScript and improve your application even more (e.g. by adding Universal Data Retrival using REST APIs) I definitely recommend to read the chapter Universal JavaScript for Web Applications on my book [Node.js Design Patterns Second Edition (Packt)](https://www.nodejsdesignpatterns.com/):

 [![Node.js Design Patterns Second Edition by Mario Casciaro and Luciano Mammino](https://cdn.scotch.io/22/v1m65E8Te2tboZO7MvOA_book-cover-nodejs-design-patterns.png)](https://www.nodejsdesignpatterns.com/)


 ## Contributing

 Everyone is very welcome to contribute to this project.
 You can contribute just by submitting bugs or suggesting improvements by
 [opening an issue](https://github.com/lmammino/judo-heroes-2/issues) or by [sending a pull request](https://github.com/lmammino/judo-heroes-2/pulls).

 ## License
 Licensed under [MIT License](LICENSE). © Luciano Mammino.
