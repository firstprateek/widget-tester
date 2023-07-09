# widget-tester

Simple project to test widgets (and other packages) by downloading them from NPM

## Getting started

Install dependencies (incl. webpack). Note: This project only defines dev dependencies.

```bash
npm i
```

Entry point is src/index.js. Built content is stored under dist/. To build your project, run:
```bash
npm run build
```

To launch development server, run:
```bash
npm run dev
```

To deploy the built index.html page to the project's github page `https://<username>.github.io/<project-name>/`, run:
```bash
npm run deploy
```
