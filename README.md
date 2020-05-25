# LitElement TypeScript starter 

This project includes a sample component using LitElement with TypeScript.

## Setup

Install dependencies:

```bash
npm i
```

## Build

This sample uses the TypeScript compiler to produce JavaScript that runs in modern browsers.

To watch files and rebuild when the files are modified, run the following command in a separate shell:

```bash
npm run tsc
```

## Dev Server

This sample uses open-wc's [es-dev-server](https://github.com/open-wc/open-wc/tree/master/packages/es-dev-server) for previewing the project without additional build steps. ES dev server handles resolving Node-style "bare" import specifiers, which aren't supported in browsers.

To run the dev server and open the project in a new browser tab:

```bash
npm run start
```

There is a development HTML file located at `/web/index.html` that you can view at http://localhost:8080/web/index.html.
