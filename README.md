<p align="center">
  <a href="#">
   <img alt="proffy" src="https://github.com/Thiago-Cardoso/proffy-nlw-02/blob/master/web/src/assets/images/logo-proffy.png?raw=true width="200">
  </a>
</p>

<p align="center">
  <a href="https://github.com/Thiago-Cardoso/proffy-nlw-02">
    <img alt="Current Version" src="https://img.shields.io/badge/version-1.0.0 -blue.svg">
  </a>
  <a href="https://pt-br.reactjs.org/">
    <img alt="" src="https://img.shields.io/badge/React-16.13.1-blue.svg" target="_blank">
  </a>

  <a href="https://nodejs.org/en/">
    <img alt="Node Version" src="https://img.shields.io/badge/node-%3E%3D%2012.0.0-brightgreen" target="_blank">
  </a>
  <a href="https://expressjs.com/pt-br/">
    <img alt="" src="https://img.shields.io/badge/Express-4.17.1-red.svg" target="_blank">
  </a>
  <a href="https://jestjs.io/">
    <img alt="" src="https://img.shields.io/badge/Typescript-3.7.2-blue.svg" target="_blank">
  </a>
  
</p>

## API
![](https://github.com/Thiago-Cardoso/proffy-nlw-02/blob/master/web/src/assets/images/nlw2-api.gif)

## Web

![](https://github.com/Thiago-Cardoso/proffy-nlw-02/blob/master/web/src/assets/images/nlw2-web.gif)

## Mobile
![](https://github.com/Thiago-Cardoso/proffy-nlw-02/blob/master/web/src/assets/images/nlw2-mobile.gif)

## Stack the Project

- **Node**
- **Express**
- **Knex.js**
- **ReactJS**
- **React-native**
- **Expo**
- **Expo-location**
- **TypeScript**
- **SQLite**

## Features

- **Web - Online study platform:** Online study platform, the teacher sells his working hours in several subjects.

- **Mobile:** In the Mobile application allows you to search the times of classes that have been scheduled

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You must have installed on your machine:

- Node
- NPM

### Installing

First step is to install the node:

```bash
# Using Ubuntu
$ curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
$ sudo apt-get install -y nodejs

# Using Debian, as root
# curl -sL https://deb.nodesource.com/setup_12.x | bash -
# apt-get install -y nodejs

```

For test if the service was installed with succeed, you can run the command for to check de version of Node:

```bash
$ node -v
# Must be have the node version: v12.17.0
$ npm -v
# Must be have the npm version: 6.14.6
```

## First steps

Follow the instructions to have a project present and able to run it locally.
After copying the repository to your machine, go to the project's root ecoleta:

1.  Run server API

```
# Acess server folder:
$ cd proffy-nlw-02/server
# run migrate 
$ yarn install
$ yarn knex:migrate

```

2.  Run Web Application

```
# Acess web folder and run:
$ cd proffy-nlw-02/web
$ yarn install
$ yarn start
```

3.  Run the Mobile app (Expo App)

```
# Go to mobile folder
$ cd proffy-nlw-02/mobile

# Install Dependencies
$ yarn install

# Run Aplication
$ yarn start
# After scan the Qrcode in the your Expo Mobile App.
```

## Authors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
[<img src="https://avatars1.githubusercontent.com/u/1753070?s=460&v=4" width="100px;"/><br /><sub><b>Thiago Cardoso</b></sub>](https://github.com/Thiago-Cardoso)<br />