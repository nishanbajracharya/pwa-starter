# PROGRESSIVE WEB APP STARTER
Progressive web app starter is a boilerplate for building your own progressive web apps. It provides with a basic content caching by using a service worker and standard manifests for devices to recognize as a PWA. For more information on PWAs, check out [this link](https://developers.google.com/web/progressive-web-apps/).

## Getting started
This project was built using the standard [create-react-app](https://www.npmjs.com/package/create-react-app) cli, which means it is built on top of Facebook's [React](https://facebook.github.io/react/) library. So anyone familiar with React.js can easily get started with this boilerplate by editing the `src/App.js` file.

### Requirements
- [Node.js](https://nodejs.org/en/) (>=v6.90)
- [React.js](https://facebook.github.io/react/) (>=15.5.4)
- [Yarn](https://yarnpkg.com/en/) (>=v0.24.6) [Optional but recommended]

### Steps to customize
- Change the package.json file to fit your project's credentials, such as `name`, `version` and `homepage`.
- Change the `index.html` file in `public/index.html`.
- Change appropriate icons in `public/` directory.
- Change values in `public/manifest.json`.
- Change `CACHE_NAME` variable in `public/service-worker.js`

### Running the app and deployment
To run the app, run the following command:
```
yarn start
```
Then open `http://localhost:3000` in a web browser.

To create a production build:
```
yarn build
```
This will setup a production ready build in the `build/` directory.


To deploy to gh-pages of the github repo (defined in `homepage` of `package.json`):
```
yarn deploy
```
