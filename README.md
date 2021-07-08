# NodeJS -Learning about the concepts
Nodejs Basics

<br>

### Necessary Commands 
---

#### ⚠️Should you want to create this project from zero, run all of the commands below, if not, just run **npm install --global yarn** and **yarn install** instead⚠️

<br>


> npm install --global yarn

> yarn init -y

> yarn add express

> yarn add nodemon -D (nodemon will make the server "listen" for any changes and automatically recompile the project and "--save-dev" will make the lib only exist in a Dev environment)





### Genral Tips
- In package.json use for example **dev** (you choose the name of the word) inside **scripts** to inform which start command will be executed when typing **yarn dev**. In the example below we use **nodemon** which will observe the changes and automatically recompile the project. Example:

```json
"scripts": {
    "dev": "nodemon src/index.js",
},
```