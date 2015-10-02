# React Universal

[![Join the chat at https://gitter.im/felguerez/react-universal](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/felguerez/react-universal?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## About

A starter kit for creating universal React applications that is built on:

1. React
2. React Router
3. Redux + Redux DevTools <3
4. Relay (Installed, not yet implemented)*
5. Sequelize + GraphQL

It also comes with a custom simple devmode that provides a terminal interface in which you can toggle tabs and view the different build processes.

## About Relay
Relay is installed in the application and the schema files exist, but the public release of Relay does not yet support universal Javascript. Of course, you're free to rip out the universal rendering in the server file.

![Terminal Shot](./docs/assets/term.png)

## Usage

1. To run in dev mode, `npm run devmode`
2. To start the production server, `npm start`
3. To stop the production server,`npm stop`
