
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/Wenderson-P/conceitos-nodejs"/>
      <img alt="Languages" src="https://img.shields.io/github/languages/count/Wenderson-P/conceitos-nodejs"/>
      <img alt="Repository size" src="https://img.shields.io/github/repo-size/Wenderson-P/conceitos-nodejs"/>
  </p>

## 📜 Table of Contents

* [About the Project](#-about-the-project)
  * [Made With](#-made-with)
  * [Routes](#-routes)
* [Getting Started](#getting-started)
  * [Requirements](#-requirements)
  * [Installation](#-installation)

## 🔎 About the project
This is a project made to training the basic of node</br>


## 🧰 Made with

-  [Node.js](https://www.nodejs.org)
-  [Express](https://expressjs.com/)
-  [Nodemon](https://nodemon.io/)
-  [UUIDv4](https://github.com/thenativeweb/uuidv4#readme)
-  [Jest](https://jestjs.io)
-  [SuperTest](https://github.com/visionmedia/supertest)


## 🚩 Routes

POST /repositories -> Add a new repository, the route receives a title,url and a tech in the body.
```
{ 
  id: "uuid",
  title: 'Desafio Node.js', 
  url: 'http://github.com/...', 
  techs: ["Node.js", "..."],
}
```

GET /repositories -> List all repositories

PUT /repositories/:id: -> Change title,url and techs passing these data in the body and the repository uuid in the parameter 

DELETE /repositories/:id: -> Delete the repository passing the uuid in the parameter

POST /repositories/:id/like: -> For each route call, increase the likes of the repository with the id passed in the parameter


## Getting Started

## 📋 Requirements

For development, you will only need Node.js and a package manager like yarn or npm, installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

### Yarn installation 
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---

## 🔌 Installation

    $ git clone https://github.com/Wenderson-P/conceitos-nodejs
    $ cd conceitos-nodejs
    $ yarn
  
