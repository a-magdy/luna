# Test app using the base luna docker image

Base luna docker image quadric/luna:base_0.0.2

The target of this folder is to create an app to test the luna base image

Start by creating a test-app docker image from this folder:
`./build-test-docker-image.sh`
or
`docker build . -f Dockerfile-test -t quadric/luna:test`

then run the image using the script:
`docker run --rm -it quadric/luna:test`

Or just ssh into the container:
`docker run --rm -it quadric/luna:test bash`