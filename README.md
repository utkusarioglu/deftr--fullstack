# deftr Fullstack Webclient Repo

This repo includes the webclient, server and the public api for the deftr
project.

## Usage

### Development

You can use `docker-compose.dev.yaml` to start the containers for development.
Please refer to individual submodules for their dockerfiles.

### Testing

You can use `docker-compose.test.yaml` to build the production containers to
manually observe the behavior of the code without having to wait for the build
report from the automation server. However, this is definitely not a stand-in
for rigorous testing and shall not be used as such.
