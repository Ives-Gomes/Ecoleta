<h1 align="center">
   ♻️ <a href="#"> ECOLETA </a>
</h1>

<h3 align="center">
    🌱 Your waste collection marketplace. We help the planet to be cleaner! 🌱
</h3>

<p align="center">
  <img alt="Yarn version" src="https://img.shields.io/badge/yarn-v1.22.4-blue">

  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-red">
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">

  <a href="https://www.linkedin.com/in/ives-moreira-8871b318a/">
    <img alt="made by Ives Moreira" src="https://img.shields.io/badge/made by-Ives Moreira-blueviolet">
  </a>
</p>

## About

♻️ Ecoleta - is a way to connect companies and entities that collect organic and inorganic waste to people who need to dispose of their waste in an ecological way.
Project developed during **NLW - Next Level Week** offered by [Rocketseat](https://blog.rocketseat.com.br/primeira-next-level-week/). NLW is an online experience with lots of practical content, challenges and hacks where the content is available for a week.

---

## Features

- [x] Companies or entities can register on the web platform by sending:

  - [x] an image of the collection point
  - [x] entity name, email and whatsapp
  - [x] and the address so that it can appear on the map
  - [x] in addition to selecting one or more collection items:
    - lamps
    - Batteries
    - papers and cardboard
    - electronic waste
    - organic waste
    - kitchen oil

- [x] Users have access to the mobile application, where they can:
  - [x] browse the map to see the registered institutions
  - [x] contact the entity via E-mail or WhatsApp

---

## How it works

This project is divided into three parts:

1. [Backend](https://github.com/Ives-Gomes/Ecoleta-API)
2. Frontend
3. [Mobile](https://github.com/Ives-Gomes/Ecoleta-Mobile)

Both Frontend and Mobile need the Backend to be running to work.

### Pre-requisites

Before you begin, you will need to have the following tools installed on your machine:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com/).
In addition, it is good to have an editor to work with the code like [VSCode](https://code.visualstudio.com/)

#### Start Frontend (web)

```bash

# Clone this repository
$ git clone https://github.com/Ives-Gomes/Ecoleta.git

# Access the project folder cmd/terminal
$ cd Ecoleta

# install the dependencies
$ yarn

# Run the application in development mode
$ yarn start

# The server will start at port: 3000 - go to http://localhost:3000

```

---

## Tech Stack

The following tools were used in the construction of the project:

#### **Website** ([React](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/))

- **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
- **[React Icons](https://react-icons.github.io/react-icons/)**
- **[Axios](https://github.com/axios/axios)**
- **[Leaflet](https://react-leaflet.js.org/en/)**
- **[React Leaflet](https://react-leaflet.js.org/)**
- **[React Dropzone](https://github.com/react-dropzone/react-dropzone)**

> See the file [package.json](https://github.com/Ives-Gomes/Ecoleta/blob/master/package.json)

#### **Utils**

- Maps: **[Leaflet](https://react-leaflet.js.org/en/)**
- Editor: **[Visual Studio Code](https://code.visualstudio.com/)** → Extensions: **[SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)**
- Icons: **[Feather Icons](https://feathericons.com/)**, **[Font Awesome](https://fontawesome.com/)**
- Fonts: **[Ubuntu](https://fonts.google.com/specimen/Ubuntu)**, **[Roboto](https://fonts.google.com/specimen/Roboto)**

---

## How to contribute

1. Fork the project.
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save your changes and create a commit message telling you what you did: `git commit -m "feature: My new feature"`
4. Submit your changes: `git push origin my-feature`

---

## Author

<a href="https://www.linkedin.com/in/ives-moreira-8871b318a/">
 <img style="border-radius: 50%;" src="https://avatars0.githubusercontent.com/u/53413719?s=460&u=1e98084c7754352365563418c0566299f52c7e39&v=4" width="100px;" alt="Ives Moreira"/>
 <br />
 <sub><b>Ives Moreira</b></sub></a> <a href="https://www.linkedin.com/in/ives-moreira-8871b318a/" title="Linkedin"></a>
 <br />

---

## License

This project is under the license [MIT](./LICENSE).

Made with 💜 by Ives Moreira.
