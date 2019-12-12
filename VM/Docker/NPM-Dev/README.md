# NPM-Dev Docker image

This docker image contains a light-weight docker image containing Node and NPM.

## General

Upon starting of the docker container it will cd into environment variable of \$PROJECT_DIR or `/workdir` by default. It will then run the command of `npm ci && npm run $SCRIPT_NAME` with \$SCRIPT_NAME default being dev

### Usage

Mount your host/docker volume into any folder path within the container. If your container volume isn't `/workdir` then you must set the environment variable of \$PROJECT_DIR to the container path that you used.
