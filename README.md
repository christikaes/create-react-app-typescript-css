# `react-scripts-ts-css` [![npm version](https://badge.fury.io/js/react-scripts-ts-css.svg)](https://badge.fury.io/js/react-scripts-ts-css)

Create React apps (with Typescript (with css modules)) with no build configuration.

_Do you know react and want to try out typescript? Or do you know typescript and want to try out react? Do you also need css modules?_ Get all the benefits from `create-react-app` but you use typescript and css modules! 🚀

## tl;dr

```sh
npm install -g create-react-app

create-react-app my-app --scripts-version=react-scripts-ts-css
cd my-app/
npm start
```

## Why use this package?
The difference between this project and react-scripts-ts-css-modules/react-scripts-ts-cssModules is that this is based on the react-scripts-ts cra fork so it's easier to maintain. Looks like CSSModules will be added to CRA soon: [pull request here](https://github.com/facebookincubator/create-react-app/pull/2285) In which case we can just update react-scripts-ts to add [typings-for-css-modules-loader](https://github.com/Jimdo/typings-for-css-modules-loader) and depricate this fork.
