# Rescript-React Template

This is:
- A template for your new ReasonReact project with the newer Rescript syntax.
- Extra helper documentation for ReasonReact (full ReasonReact docs [here](https://reasonml.github.io/reason-react/)).
- Compiles & watches SASS in the webpack build.

`src` contains 4 sub-folders, each an independent, self-contained ReasonReact example. Feel free to delete any of them and shape this into your project! This template's more malleable than you might be used to =).

## Run

```sh
npm install
npm run server
# in a new tab
npm start
```

Open a new web page to `http://localhost:8000/`. Change any `.res` file in `src` to see the page auto-reload.

## Usage

```
open Utils

requireCSS('./style.css') // loads css/sass files
requireImage('./image.png') // loads images
```

# Bundle for Production

```sh
npm run build
```

# Handle Routing Yourself

ReasonReact comes with a small [router](https://reasonml.github.io/reason-react/docs/en/router) you might be interested in.
