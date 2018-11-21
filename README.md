# ifbooks
IFBooks is an application that connects book sellers to buyers. Book sellers or author create a shop, add book to their sthelf for customer to buy

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:
* Git - [Download & Install Git](https://git-scm.com/downloads). OSX and Linux machines typically have this already installed.
* Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager. If you encounter any problems, you can also use this [GitHub Gist](https://gist.github.com/isaacs/579814) to install Node.js.
* MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads), and make sure it's running on the default port (27017).

#### Cloning The GitHub Repository
The recommended way to get MEAN.js is to use git to directly clone the MEAN.JS repository:

```bash
$ git clone https://github.com/ilasisi/ifbooks.git
```
After cloning, then run
```bash
$ npm install
```
This command does a few things:
* First it will install the dependencies needed for the application to run.
* If you're running in a development environment, it will then also install development dependencies needed for testing and running your application.
* To update these packages later on, just run `npm update`

## Running Your Application

Run your application using npm:

```bash
$ npm start

The application should run on port 3000 with the *development* environment configuration, so in your browser just go to [http://localhost:3000](http://localhost:3000).
API server is on [http://localhost:3000/api](http://localhost:3000/api)