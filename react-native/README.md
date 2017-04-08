react-native
=

A dockerfile for react-native.

Use `docker build -t SOME_NAME --build-arg NAME=SOME_NAME .`, to set up a docker image with a react-native-app called `SOME_NAME`. Then use `docker run -t SOME_NAME` to start up a container.

Or, of course, use the `build-run SOME_NAME`, this will do the same for ya.
