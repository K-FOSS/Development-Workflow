# Fetcher Docker images (WIP)

Currently this docker image is a service used for cloning a Git repo upon the starting of the container

## Future

In the future I want this to also fetch the repo if already cloned.

## Usage

To use this image you need to set the \$GIT_REPO to the repo of the Git repo you would like to clone. If auth is needed it must be included in the HTTPS repo URI.
