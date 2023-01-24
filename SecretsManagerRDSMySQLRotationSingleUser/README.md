# How to Build

Run `dockerbuild.sh` which will build the image in this dir. Pass it the `$DOCKER_TAG` env var to send it to the right registry.

Example:

```
DOCKER_TAG="<docker_registry>/<image_name>:<image_tag>" ./dockerbuild.sh
```