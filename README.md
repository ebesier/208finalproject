# 208 Final Project

### Running the Dockerfile on a Local Machine
To run it on your local machine, 

1. Download Docker and create a Docker account. 
2. [**Skip to this step if you already have Docker downloaded**] Download the .zip file in this repository, unzip it, and navigate to the resulting folder in your terminal. 
3. Make sure Docker is running in the background and run the following commands:

```export DOCKER_BUILDKIT=0```

```export COMPOSE_DOCKER_CLI_BUILD=0```

```docker build -t project .```

```docker run -p 8888:8888 project```

Finally, copy and paste one of the URLs into your browser. This will launch you into the Jupyter notebook! Make sure to download the edited notebook to your local computer before leaving the session. 

### Sythetic datasets

#### Netflix

- first version -> `checkpoints` {epsilon: 338.63 , accuracy: 53.85%}

- updated version -> `checkpoints_6` {epsilon: 29.92, accuracy: 49.72%}

#### PUMs

- first version -> `checkpoints_PUMs` {epsilon: 158.48 , accuracy: 60.8%}

- updated version -> `checkpoints_7` {epsilon: 19.2, accuracy: 68.3%}

    - The weird decrease in espilon in accuracy could potentially be attributed to teh fact that in the second batch I exclude the index column
