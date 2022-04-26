# 208 Final Project

### Running the Dockerfile on a Local Machine
To run it on your local machine, 

1. Download Docker and create a Docker account. 
2. [**Skip to this step if you already have Docker downloaded**] Download the .zip file in this repository, unzip it, and navigate to the resulting folder in your terminal. 
3. Make sure Docker is running in the background and run the following commands:

```export DOCKER_BUILDKIT=0```

```export COMPOSE_DOCKER_CLI_BUILD=0```

```docker build -t image .```

```docker run -p 8888:8888 image```

Finally, copy and paste one of the URLs into your browser. This will launch you into the Jupyter notebook! Make sure to download the edited notebook to your local computer before leaving the session. 
