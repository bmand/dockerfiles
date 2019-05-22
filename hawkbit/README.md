
Dockerfile used to generate a docker container for the hawkbit server

$ docker run --name hawkbit weatherfmu/hawkbit:latest

# Get this image
The recommended way to get the Weatherfmu Hawkbit Docker Image is to pull the prebuilt image from the Docker Hub Registry.

$ docker pull weatherfmu/hawkbit:latest

If you wish, you can also build the image yourself by cloning the repository, changing to the directory containing the Dockerfile and executing the docker build command.

$ git clone https://github.com/bmand/weather-fmu-dockerfiles.git
$ cd hawkbit
$ docker build -t weatherfmu/hawkbit:latest .
