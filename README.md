# [draftjs_exporter_demo](https://draftjs-exporter.herokuapp.com/)

> A demo of [draftjs_exporter](https://github.com/springload/draftjs_exporter) and [draftail](https://github.com/springload/draftail) running together

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
python app.py
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

The demo is [on Heroku](https://draftjs-exporter.herokuapp.com/). It uses two buildpacks. Use `heroku buildpacks` to manage those.