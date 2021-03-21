# firebase-ci-cd [![CI](https://github.com/manasanavada/firebase-ci-cd/actions/workflows/main.yml/badge.svg)](https://github.com/manasanavada/firebase-ci-cd/actions/workflows/main.yml)

### Install firebase tools globally and login

`yarn add firebase-tools -g`
`firebase login`

### Initializing firebase project

- First create a project in firebase console. Then,
  `mkdir firebase-ci-cd`
  `cd firebase-ci-cd`
  `firebase init`

In the project set up phase, choose the option
`Use an existing project` and choose the project previously created using firebase console.

For all other options, choose default options.

(Also had to tweak some eslint settings, add prettier config)
