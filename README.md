# Workshop API Testing in Javascript

In this project I´ve implemented all the steps of this [AgileTestingColombia - API Workshop Js](https://github.com/AgileTestingColombia/workshop-api-testing-js).

## Setup

To run this project using npm:

```
$ npm install
$ npm start
```

## Features

- **Tests**: Test GitHub API using Mocha and Chai. Methods tested: Get, Patch, Post, Put, Head and Delete. Some methods requiered authentication which was also implemented with OAuth2 tokens.
- **Continuous integration**: I configured Travis for CI.
- **Report**: Mochawesome.
- **Static code analysis**: I used Eslint.
- **Others**: I also used isomophic-fetch as another way to consume the API.