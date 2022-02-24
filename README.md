# Multiple Entry-Points Example For CRA and CRACO

### This is an example on how to create muliple entries to an isolated page, different to main entry (home->index.js->App.js). It could run unauthenticated from your home page. Used a plain `create-react-app` v5 using vanilla JS and CRACO. I run it with both React 4 and 5 by uncommenting the 2 obvious lines of code in `craco.config.js` ()..

This is a simplified version using [cra-multi-entry-demo](https://github.com/helsonxiao/cra-multi-entry-demo). Thank you *helsonxiao* you saved my butt.


This project was bootstrapped with Create React App.

Available Pages (URI's):
```
/
/albuminfo
/sound 
/sign-off
```

### Available Scripts
In the project directory, you can run:

`yarn build:craco` or 
`npm run build:craco`

Build the app with CRACO and creates your new entries for production (checkout the build directory with your URI).

`yarn start:craco` or
`npm start:craco`

Runs the app with CRACO and lets you test the app in dev mode (hot reload in port 3000 by def).

### Refernece to other Github projects that have different approaches:

1. `react-app-rewire-multiple-entry`
1. `react-app-rewired`
1. `cra-multi-entry-demo`
