<div align="center">
  <img style="border-radius:50%;" src="https://github.com/sestevao/chatty/blob/main/.github/chat-bot.jpg?raw=true" width=150 />
</div>

<h2 align="center">Real time support chat with websockets</h2>

<p align="center" style="color:lightblue; font-style:italic;">“What we know is a drop. What we ignore is an ocean.” - <em>Isaac Newton</em></p>

</br>

## 💻 About the Project

The support-chat is an app that offers a real-time support chat (like those E-commerce chats)

This project was developed during the Node.js path in the fifth edition of NLW (Next Level Week). We learned concepts about what is an API, starting a project using Typescript and Express for route management.

<img src="https://github.com/sestevao/chatty/blob/main/.github/Animation.gif?raw=true" alt="projeto">

<br>

## 🚀 Features

- [x] Administrator
  - [x] Turn chat on and off
  - [x] Check which users have not yet been served
  - [x] Upon entering the service the user leaves the list of pending
  - [x] Receive and send messages in real time
- [x] Client
  - [x] Enter chat
  - [x] Receive and send messages in real time

<br>

## ✨ Technologies

In this project we use:

- [Express](https://expressjs.com/), as Node.js framework
- [Typescript](https://www.typescriptlang.org/), to add static types definitions.
- [TypeORM](https://typeorm.io/#/), as way to communicate with databases.
- [Socket.io](https://socket.io/), for realtime communication.
- [SQLite](https://www.sqlite.org/index.html), as SQL database.
- [Mustache](https://mustache.github.io/)

<br>

## ❗️ Requisites

To run application we need have installed:

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/) (Optional)
- [Beekeeper Studio](https://www.beekeeperstudio.io/)
- [Insomnia](https://insomnia.rest/)

<br>

## ⚡ How to run

- Clone this repo
- Install all dependencies with `yarn`
- Install the migrations `yarn typeorm migration:run`
- Start the server with `yarn dev`

To run this app in a web browser
navigate to `localhost:3333/pages/admin` and `localhost:3333/pages/client` and enjoy sending messages.

Can access using the https://chatty-nodejs.netlify.com

<br>

## 📚 Environment Configuration:

- [Trilha NodeJS - Notion](https://www.notion.so/Trilha-Node-js-0b238db0256c4ce889df0e9ce92f4a68)

- [My notes on Notion](https://www.notion.so/Trilha-Node-js-99e5035e5dfb425fa86292f91ff352ba)
