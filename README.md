# `Applicant-manager`

This project is bootstrapped by [aurelia-cli](https://github.com/aurelia/cli).

For more information, go to https://aurelia.io/docs/cli/webpack

## Run app

Download "Applicant-manager.zip" file and extract to your local folder. Once extraction is completed then "Goto -> Applicant-manager" folder and open Git bash or cmd prompt and type "npm install" to download all node modules.

Once all the node modules are successfully download. Run the application using `npm start or au run` or follow below steps.

Run `npm start`, then open `http://localhost:8080`

## Modify the End point

Goto "src/resources/api-service.ts" folder inside Application manager. Modify this url value into your service end point url like this `url: string = 'https://localhost:5001'.

Save the changes and run the app with `au run or npm start`.
..............................................................................................................................................................................

You can change the standard webpack configurations from CLI easily with something like this: `npm start -- --open --port 8888`. However, it is better to change the respective npm scripts or `webpack.config.js` with these options, as per your need.

To enable Webpack Bundle Analyzer, do `npm run analyze` (production build).

To enable hot module reload, do `npm start -- --hmr`.

To change dev server port, do `npm start -- --port 8888`.

To change dev server host, do `npm start -- --host 127.0.0.1`

**PS:** You could mix all the flags as well, `npm start -- --host 127.0.0.1 --port 7070 --open --hmr`

For long time aurelia-cli user, you can still use `au run` with those arguments like `au run --env prod --open --hmr`. But `au run` now simply executes `npm start` command.

## Build for production

Run `npm run build`, or the old way `au build --env prod`.

To run in watch mode, `au test --watch` or `au jest --watch`.
