# Cloud Functions ES6 Starter
> Sample project to deploy ES6 project to Google Cloud Functions.
## Configuration

Warning ! You need NodeJS 6 LTS.
You can switch NPM versions with [NVM](https://github.com/creationix/nvm).

## Deployment

You need to install the [gcloud binary](https://cloud.google.com/sdk/docs/quickstarts) and have it available it in PATH.
Then configure it.

`gcloud init`

## Local development

You need to install the Cloud Function emulator.

`npm install -g @google-cloud/functions-emulator`


## Usage

`npm run deploy`: Deploy project to Cloud Function.

`npm run local_deploy`: Deploy project to local server.


`npm run init_server`: Init local server for local development.

`npm run kill_server`: Kill local server.

`npm run start_server`: Start local server.

`npm run stop_server`: Stop local server.

`npm run local_call`: Call local function.


### ToDo

- [ ] Adding ES6 support with Babel.

