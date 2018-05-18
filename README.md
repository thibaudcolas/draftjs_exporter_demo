# [Draft.js exporter demo](https://draftail-playground.herokuapp.com/)

> A [demo](https://draftail-playground.herokuapp.com/) of [draftjs_exporter](https://github.com/springload/draftjs_exporter) and [Draftail](https://github.com/springload/draftail) used together.

## Deprecated

This demo has now been replaced with a new editor-focused playground, that still integrates the exporter: [https://github.com/thibaudcolas/draftail-playground](https://github.com/thibaudcolas/draftail-playground).

## Install

From the command-line:

```sh
git clone git@github.com:springload/draftjs_exporter_demo.git
cd draftjs_exporter_demo
virtualenv .venv
source ./.venv/bin/activate
pip install -r requirements.txt
nvm install
# Then, install all project dependencies.
npm install
npm run start
```

## Working on the project

> Everything mentioned in the installation process should already be done.

```sh
# Make sure you use the right node version.
nvm use
# Start the server and the development tools.
npm run start
# Builds frontend assets.
npm run build
# View other available commands with:
npm run
```

## Deployment

> The demo is [on Heroku](https://draftail-playground.herokuapp.com/).

It uses two buildpacks: `heroku/nodejs` and `heroku/python`, and is configured to automatically deploy after each push on `master`.
