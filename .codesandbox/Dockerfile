FROM tensorflow/tensorflow:latest-jupyter

RUN curl -L https://github.com/docker/compose/releases/download/1.24.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose && chmod +x /usr/local/bin/docker-compose

RUN apt-get update && apt-get install -y python3-opencv
RUN pip install opencv-python tqdm easydict