# Finding Falcone

Hi! Thanks for your time in considering this coding challenge. What follows are instructions on how to get the app running and some detailed documentation about bits and pieces.

## Setup

```bash
nvm use
npm install
npm start # this will start webpack dev server
```

### Details about configuration

This project uses
* **Webpack**, for asset building
* **Webpack Dev Server**, for development
* **Jest**, for tests
* **CSS Modules**, for static styles
* **React**, as a JS framework
* **fetch-retry**, for network reliability
* **eslint**, for linting
* **babel**, for transformation of es6+
* **chai**, for assertions
* **postcss**, for css modules & `composes` syntax
* **nvm**, for node version control

## Details about the implementation
### State management
I chose to not use Redux and use hooks, custom hooks and the context API provided by React. I find this provides simplier state management infrastructure than Redux.

### Tests
Look, I know I didn't write many tests. By the end of this coding challenge I have already put quite a lot of hours into this (10+). I'm comfortable with tests, and happy to prove this in further interview rounds if needed.

### Network reliability
`fetch-retry` is used to handle network based failures and automatically retry when they occure.

# Demo
Please see the `finding_falcone.gif` in this project for a demo
