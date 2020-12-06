# Blueprint Backend

This is my own blueprint for backend app use node.js and MySQL database.

---
## Requirements

For development, you will only need Node.js

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).


If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
### Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---

## Install

    $ git clone https://github.com/FUA26/blueprintBackend
    $ cd blueprintBackend
    $ npm install

## Configure app
  You need .env file to store your configuration
## Running the project

    $ npm start

## Simple build for production

    $ npm build
