# R and D

## Webpack

Run `npx webpack`, which will take our script at `src/index.js` as the entry point, and will generate `dist/main.js` as the output. The `npx` command, which ships with Node 8.2/npm 5.2.0 or higher, runs the webpack binary (`./node_modules/.bin/webpack`) of the webpack package.

Run with a config: `npx webpack --config webpack.config.js`

By adding `"build":"webpack"` to scripts, the `npm run build` command can be used in place of the `npx` command.

## Cypress

### Opening Cypress
Run this command to open the Cypress: `npx cypress open`
